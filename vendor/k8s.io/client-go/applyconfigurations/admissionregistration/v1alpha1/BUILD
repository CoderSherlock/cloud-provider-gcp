load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "v1alpha1",
    srcs = [
        "admissionpolicyspec.go",
        "matchresources.go",
        "namedrulewithoperations.go",
        "paramkind.go",
        "paramref.go",
        "paramsource.go",
        "rule.go",
        "rulewithoperations.go",
        "validatingadmissionpolicy.go",
        "validatingadmissionpolicybinding.go",
        "validatingadmissionpolicybindingspec.go",
        "validatingadmissionpolicyspec.go",
        "validation.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/applyconfigurations/admissionregistration/v1alpha1",
    importpath = "k8s.io/client-go/applyconfigurations/admissionregistration/v1alpha1",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/api/admissionregistration/v1:admissionregistration",
        "//vendor/k8s.io/api/admissionregistration/v1alpha1",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/util/managedfields",
        "//vendor/k8s.io/client-go/applyconfigurations/admissionregistration/v1:admissionregistration",
        "//vendor/k8s.io/client-go/applyconfigurations/internal",
        "//vendor/k8s.io/client-go/applyconfigurations/meta/v1:meta",
    ],
)
