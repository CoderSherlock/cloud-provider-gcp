load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "status",
    srcs = ["status.pb.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/genproto/googleapis/rpc/status",
    importpath = "google.golang.org/genproto/googleapis/rpc/status",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl",
        "//vendor/google.golang.org/protobuf/types/known/anypb",
    ],
)
