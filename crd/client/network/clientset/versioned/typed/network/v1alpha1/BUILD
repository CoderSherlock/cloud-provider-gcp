load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v1alpha1",
    srcs = [
        "doc.go",
        "generated_expansion.go",
        "gkenetworkparamset.go",
        "gkenetworkparamsetlist.go",
        "network.go",
        "network_client.go",
        "networkinterface.go",
        "networkinterfacelist.go",
        "networklist.go",
    ],
    importpath = "k8s.io/cloud-provider-gcp/crd/client/network/clientset/versioned/typed/network/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/cloud-provider-gcp/crd/apis/network/v1alpha1",
        "//vendor/k8s.io/cloud-provider-gcp/crd/client/network/clientset/versioned/scheme",
    ],
)
