load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "width",
    srcs = [
        "kind_string.go",
        "tables10.0.0.go",
        "tables11.0.0.go",
        "tables12.0.0.go",
        "tables13.0.0.go",
        "tables9.0.0.go",
        "transform.go",
        "trieval.go",
        "width.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/text/width",
    importpath = "golang.org/x/text/width",
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/text/transform"],
)
