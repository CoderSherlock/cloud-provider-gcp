load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "fake",
    srcs = [
        "doc.go",
        "fake_daemonset.go",
        "fake_deployment.go",
        "fake_deployment_expansion.go",
        "fake_extensions_client.go",
        "fake_ingress.go",
        "fake_networkpolicy.go",
        "fake_podsecuritypolicy.go",
        "fake_replicaset.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/kubernetes/typed/extensions/v1beta1/fake",
    importpath = "k8s.io/client-go/kubernetes/typed/extensions/v1beta1/fake",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/extensions/v1beta1",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/labels",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/applyconfigurations/extensions/v1beta1",
        "//vendor/k8s.io/client-go/kubernetes/typed/extensions/v1beta1",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/testing",
    ],
)
