load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "resourcelock",
    srcs = [
        "configmaplock.go",
        "endpointslock.go",
        "interface.go",
        "leaselock.go",
        "multilock.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/tools/leaderelection/resourcelock",
    importpath = "k8s.io/client-go/tools/leaderelection/resourcelock",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/coordination/v1:coordination",
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/api/errors",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/client-go/kubernetes",
        "//vendor/k8s.io/client-go/kubernetes/typed/coordination/v1:coordination",
        "//vendor/k8s.io/client-go/kubernetes/typed/core/v1:core",
        "//vendor/k8s.io/client-go/rest",
    ],
)
