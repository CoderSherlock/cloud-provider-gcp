load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "fake",
    srcs = [
        "doc.go",
        "fake_ingress.go",
        "fake_ingressclass.go",
        "fake_networking_client.go",
        "fake_networkpolicy.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/networking/v1/fake",
    importpath = "k8s.io/client-go/kubernetes/typed/networking/v1/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/networking/v1:networking",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/applyconfigurations/networking/v1:networking",
        "//vendor/k8s.io/client-go/kubernetes/typed/networking/v1:networking",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/testing",
    ],
)
