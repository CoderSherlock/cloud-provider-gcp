load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "annotations",
    srcs = [
        "annotations.pb.go",
        "client.pb.go",
        "field_behavior.pb.go",
        "http.pb.go",
        "resource.pb.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/genproto/googleapis/api/annotations",
    importpath = "google.golang.org/genproto/googleapis/api/annotations",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/golang/protobuf/proto",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl",
        "//vendor/google.golang.org/protobuf/types/descriptorpb",
    ],
)
