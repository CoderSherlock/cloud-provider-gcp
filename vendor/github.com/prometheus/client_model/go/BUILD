load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go",
    srcs = ["metrics.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/prometheus/client_model/go",
    importpath = "github.com/prometheus/client_model/go",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/github.com/golang/protobuf/ptypes/timestamp",
    ],
)
