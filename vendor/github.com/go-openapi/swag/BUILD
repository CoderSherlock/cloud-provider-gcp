load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "swag",
    srcs = [
        "convert.go",
        "convert_types.go",
        "doc.go",
        "json.go",
        "loading.go",
        "name_lexem.go",
        "net.go",
        "path.go",
        "post_go18.go",
        "post_go19.go",
        "pre_go18.go",
        "pre_go19.go",
        "split.go",
        "util.go",
        "yaml.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/go-openapi/swag",
    importpath = "github.com/go-openapi/swag",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/mailru/easyjson/jlexer",
        "//vendor/github.com/mailru/easyjson/jwriter",
        "//vendor/gopkg.in/yaml.v2:yaml_v2",
    ],
)
