load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "mousetrap",
    srcs = [
        "trap_others.go",
        "trap_windows.go",
        "trap_windows_1.4.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/inconshreveable/mousetrap",
    importpath = "github.com/inconshreveable/mousetrap",
    visibility = ["//visibility:public"],
)
