load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "gcexportdata",
    srcs = [
        "gcexportdata.go",
        "importer.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/tools/go/gcexportdata",
    importpath = "golang.org/x/tools/go/gcexportdata",
    visibility = ["//visibility:public"],
    deps = ["//vendor/golang.org/x/tools/go/internal/gcimporter"],
)
