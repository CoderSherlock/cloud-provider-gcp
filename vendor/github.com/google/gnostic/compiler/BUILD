load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "compiler",
    srcs = [
        "context.go",
        "error.go",
        "extensions.go",
        "helpers.go",
        "main.go",
        "reader.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/gnostic/compiler",
    importpath = "github.com/google/gnostic/compiler",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/github.com/golang/protobuf/ptypes/any",
        "//vendor/github.com/google/gnostic/extensions",
        "//vendor/github.com/google/gnostic/jsonschema",
        "//vendor/gopkg.in/yaml.v3:yaml_v3",
    ],
)
