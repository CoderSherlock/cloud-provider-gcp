load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "norm",
    srcs = [
        "composition.go",
        "forminfo.go",
        "input.go",
        "iter.go",
        "normalize.go",
        "readwriter.go",
        "tables10.0.0.go",
        "tables11.0.0.go",
        "tables12.0.0.go",
        "tables13.0.0.go",
        "tables9.0.0.go",
        "transform.go",
        "trie.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/text/unicode/norm",
    importpath = "golang.org/x/text/unicode/norm",
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/text/transform"],
)
