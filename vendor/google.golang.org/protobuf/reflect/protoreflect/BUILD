load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "protoreflect",
    srcs = [
        "methods.go",
        "proto.go",
        "source.go",
        "source_gen.go",
        "type.go",
        "value.go",
        "value_union.go",
        "value_unsafe.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/protobuf/reflect/protoreflect",
    importpath = "google.golang.org/protobuf/reflect/protoreflect",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/google.golang.org/protobuf/encoding/protowire",
        "//vendor/google.golang.org/protobuf/internal/pragma",
    ],
)
