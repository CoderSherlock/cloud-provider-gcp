load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "flowcontrol",
    srcs = ["interface.go"],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/informers/flowcontrol",
    importpath = "k8s.io/client-go/informers/flowcontrol",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/client-go/informers/flowcontrol/v1alpha1",
        "//vendor/k8s.io/client-go/informers/flowcontrol/v1beta1",
        "//vendor/k8s.io/client-go/informers/flowcontrol/v1beta2",
        "//vendor/k8s.io/client-go/informers/flowcontrol/v1beta3",
        "//vendor/k8s.io/client-go/informers/internalinterfaces",
    ],
)
