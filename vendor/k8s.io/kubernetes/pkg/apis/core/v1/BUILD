load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "core",
    srcs = [
        "conversion.go",
        "defaults.go",
        "doc.go",
        "register.go",
        "zz_generated.conversion.go",
        "zz_generated.defaults.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/kubernetes/pkg/apis/core/v1",
    importpath = "k8s.io/kubernetes/pkg/apis/core/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/core/v1:core",
        "//vendor/k8s.io/apimachinery/pkg/api/resource",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/conversion",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/intstr",
        "//vendor/k8s.io/apimachinery/pkg/util/validation/field",
        "//vendor/k8s.io/kubernetes/pkg/apis/apps",
        "//vendor/k8s.io/kubernetes/pkg/apis/core",
        "//vendor/k8s.io/kubernetes/pkg/util/parsers",
        "//vendor/k8s.io/utils/pointer",
    ],
)
