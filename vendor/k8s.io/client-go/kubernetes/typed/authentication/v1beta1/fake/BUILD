load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "fake",
    srcs = [
        "doc.go",
        "fake_authentication_client.go",
        "fake_tokenreview.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/authentication/v1beta1/fake",
    importpath = "k8s.io/client-go/kubernetes/typed/authentication/v1beta1/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/authentication/v1beta1",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/client-go/kubernetes/typed/authentication/v1beta1",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/testing",
    ],
)
