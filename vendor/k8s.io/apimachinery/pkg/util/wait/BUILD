load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "wait",
    srcs = [
        "doc.go",
        "wait.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apimachinery/pkg/util/wait",
    importpath = "k8s.io/apimachinery/pkg/util/wait",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/utils/clock",
    ],
)
