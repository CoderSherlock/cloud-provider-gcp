load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v1alpha1",
    srcs = [
        "csistoragecapacity.go",
        "volumeattachment.go",
        "volumeattachmentsource.go",
        "volumeattachmentspec.go",
        "volumeattachmentstatus.go",
        "volumeerror.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/applyconfigurations/storage/v1alpha1",
    importpath = "k8s.io/client-go/applyconfigurations/storage/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/storage/v1alpha1",
        "//vendor/k8s.io/apimachinery/pkg/api/resource",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields",
        "//vendor/k8s.io/client-go/applyconfigurations/core/v1:core",
        "//vendor/k8s.io/client-go/applyconfigurations/internal",
        "//vendor/k8s.io/client-go/applyconfigurations/meta/v1:meta",
    ],
)
