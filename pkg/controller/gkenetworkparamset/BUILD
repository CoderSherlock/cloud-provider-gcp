load("@io_bazel_rules_go//go:def.bzl", "go_library", "go_test")

go_library(
    name = "gkenetworkparamset",
    srcs = ["gkenetworkparamset_controller.go"],
    importpath = "k8s.io/cloud-provider-gcp/pkg/controller/gkenetworkparamset",
    visibility = ["//visibility:public"],
    deps = [
        "//providers/gce",
        "//vendor/google.golang.org/api/compute/v1:compute",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/util/runtime",
        "//vendor/k8s.io/apimachinery/pkg/util/wait",
        "//vendor/k8s.io/client-go/tools/cache",
        "//vendor/k8s.io/client-go/util/workqueue",
        "//vendor/k8s.io/cloud-provider-gcp/crd/apis/network/v1alpha1",
        "//vendor/k8s.io/cloud-provider-gcp/crd/client/network/clientset/versioned",
        "//vendor/k8s.io/cloud-provider-gcp/crd/client/network/clientset/versioned/typed/network/v1alpha1",
        "//vendor/k8s.io/component-base/metrics/prometheus/controllers",
        "//vendor/k8s.io/klog/v2:klog",
    ],
)

go_test(
    name = "gkenetworkparamset_test",
    srcs = ["gkenetworkparamset_controller_test.go"],
    embed = [":gkenetworkparamset"],
    deps = [
        "//providers/gce",
        "//vendor/github.com/GoogleCloudPlatform/k8s-cloud-provider/pkg/cloud/meta",
        "//vendor/github.com/onsi/gomega",
        "//vendor/google.golang.org/api/compute/v1:compute",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/client-go/tools/cache",
        "//vendor/k8s.io/cloud-provider-gcp/crd/apis/network/v1alpha1",
        "//vendor/k8s.io/cloud-provider-gcp/crd/client/network/clientset/versioned/fake",
        "//vendor/k8s.io/cloud-provider-gcp/crd/client/network/informers/externalversions/network/v1alpha1",
        "//vendor/k8s.io/component-base/metrics/prometheus/controllers",
    ],
)
