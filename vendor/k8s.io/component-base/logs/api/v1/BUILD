load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "api",
    srcs = [
        "doc.go",
        "kube_features.go",
        "options.go",
        "pflags.go",
        "registry.go",
        "types.go",
        "zz_generated.deepcopy.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/component-base/logs/api/v1",
    importpath = "k8s.io/component-base/logs/api/v1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/go-logr/logr",
        "//vendor/github.com/spf13/pflag",
        "//vendor/k8s.io/apimachinery/pkg/api/resource",
        "//vendor/k8s.io/apimachinery/pkg/util/validation/field",
        "//vendor/k8s.io/component-base/cli/flag",
        "//vendor/k8s.io/component-base/featuregate",
        "//vendor/k8s.io/component-base/logs/klogflags",
        "//vendor/k8s.io/klog/v2:klog",
    ],
)
