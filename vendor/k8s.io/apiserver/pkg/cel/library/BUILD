load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "library",
    srcs = [
        "cost.go",
        "libraries.go",
        "lists.go",
        "regex.go",
        "urls.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/apiserver/pkg/cel/library",
    importpath = "k8s.io/apiserver/pkg/cel/library",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/google/cel-go/cel",
        "//vendor/github.com/google/cel-go/checker",
        "//vendor/github.com/google/cel-go/common",
        "//vendor/github.com/google/cel-go/common/types",
        "//vendor/github.com/google/cel-go/common/types/ref",
        "//vendor/github.com/google/cel-go/common/types/traits",
        "//vendor/github.com/google/cel-go/ext",
        "//vendor/github.com/google/cel-go/interpreter",
        "//vendor/github.com/google/cel-go/interpreter/functions",
        "//vendor/google.golang.org/genproto/googleapis/api/expr/v1alpha1",
        "//vendor/k8s.io/apiserver/pkg/cel",
    ],
)
