load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "apierror",
    srcs = ["apierror.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/github.com/googleapis/gax-go/v2/apierror",
    importpath = "github.com/googleapis/gax-go/v2/apierror",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/googleapis/gax-go/v2/apierror/internal/proto",
        "//vendor/google.golang.org/api/googleapi",
        "//vendor/google.golang.org/genproto/googleapis/rpc/errdetails",
        "//vendor/google.golang.org/grpc/status",
        "//vendor/google.golang.org/protobuf/encoding/protojson",
    ],
)
