load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "credentials",
    srcs = [
        "credentials.go",
        "go12.go",
        "tls.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/grpc/credentials",
    importpath = "google.golang.org/grpc/credentials",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/google.golang.org/grpc/attributes",
        "//vendor/google.golang.org/grpc/internal",
        "//vendor/google.golang.org/grpc/internal/credentials",
    ],
)
