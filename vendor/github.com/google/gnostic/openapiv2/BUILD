load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "openapiv2",
    srcs = [
        "OpenAPIv2.go",
        "OpenAPIv2.pb.go",
        "document.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/google/gnostic/openapiv2",
    importpath = "github.com/google/gnostic/openapiv2",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/gnostic/compiler",
        "//vendor/google.golang.org/protobuf/reflect/protoreflect",
        "//vendor/google.golang.org/protobuf/runtime/protoimpl",
        "//vendor/google.golang.org/protobuf/types/known/anypb",
        "//vendor/gopkg.in/yaml.v3:yaml_v3",
    ],
)
