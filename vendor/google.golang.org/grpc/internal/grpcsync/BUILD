load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "grpcsync",
    srcs = ["event.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/internal/grpcsync",
    importpath = "google.golang.org/grpc/internal/grpcsync",
    visibility = ["//vendor/google.golang.org/grpc:__subpackages__"],
)
