load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "credentials",
    srcs = [
        "spiffe.go",
        "syscallconn.go",
        "util.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/internal/credentials",
    importpath = "google.golang.org/grpc/internal/credentials",
    visibility = ["//vendor/google.golang.org/grpc:__subpackages__"],
    deps = ["//vendor/google.golang.org/grpc/grpclog"],
)
