load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "code",
    srcs = ["code.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/genproto/googleapis/rpc/code",
    importpath = "google.golang.org/genproto/googleapis/rpc/code",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl",
    ],
)
