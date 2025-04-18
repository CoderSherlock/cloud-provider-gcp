load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "metrics",
    srcs = [
        "buckets.go",
        "collector.go",
        "counter.go",
        "desc.go",
        "gauge.go",
        "histogram.go",
        "http.go",
        "labels.go",
        "metric.go",
        "options.go",
        "opts.go",
        "processstarttime.go",
        "processstarttime_others.go",
        "processstarttime_windows.go",
        "registry.go",
        "summary.go",
        "timing_histogram.go",
        "value.go",
        "version.go",
        "version_parser.go",
        "wrappers.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/component-base/metrics",
    importpath = "k8s.io/component-base/metrics",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/github.com/blang/semver/v4:semver",
        "//vendor/github.com/prometheus/client_golang/prometheus",
        "//vendor/github.com/prometheus/client_golang/prometheus/promhttp",
        "//vendor/github.com/prometheus/client_model/go",
        "//vendor/github.com/spf13/pflag",
        "//vendor/k8s.io/apimachinery/pkg/util/sets",
        "//vendor/k8s.io/apimachinery/pkg/version",
        "//vendor/k8s.io/component-base/metrics/prometheusextension",
        "//vendor/k8s.io/component-base/version",
        "//vendor/k8s.io/klog/v2:klog",
    ] + select({
        "@io_bazel_rules_go//go/platform:aix": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:android": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:darwin": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:dragonfly": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:freebsd": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:illumos": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:ios": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:js": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:linux": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:netbsd": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:openbsd": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:plan9": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:solaris": [
            "//vendor/github.com/prometheus/procfs",
        ],
        "@io_bazel_rules_go//go/platform:windows": [
            "//vendor/golang.org/x/sys/windows",
        ],
        "//conditions:default": [],
    }),
)
