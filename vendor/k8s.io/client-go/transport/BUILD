load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "transport",
    srcs = [
        "cache.go",
        "cache_go118.go",
        "cert_rotation.go",
        "config.go",
        "round_trippers.go",
        "token_source.go",
        "transport.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/transport",
    importpath = "k8s.io/client-go/transport",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/golang.org/x/oauth2",
        "//vendor/k8s.io/apimachinery/pkg/util/net",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/wait",
        "//vendor/k8s.io/client-go/util/connrotation",
        "//vendor/k8s.io/client-go/util/workqueue",
        "//vendor/k8s.io/klog/v2:klog",
    ],
)
