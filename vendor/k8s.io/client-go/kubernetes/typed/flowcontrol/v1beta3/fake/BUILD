load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "fake",
    srcs = [
        "doc.go",
        "fake_flowcontrol_client.go",
        "fake_flowschema.go",
        "fake_prioritylevelconfiguration.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/flowcontrol/v1beta3/fake",
    importpath = "k8s.io/client-go/kubernetes/typed/flowcontrol/v1beta3/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/flowcontrol/v1beta3",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/applyconfigurations/flowcontrol/v1beta3",
        "//vendor/k8s.io/client-go/kubernetes/typed/flowcontrol/v1beta3",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/testing",
    ],
)
