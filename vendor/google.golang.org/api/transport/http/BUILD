load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "http",
    srcs = [
        "configure_http2_go116.go",
        "configure_http2_not_go116.go",
        "default_transport_go113.go",
        "default_transport_not_go113.go",
        "dial.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/api/transport/http",
    importpath = "google.golang.org/api/transport/http",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/go.opencensus.io/plugin/ochttp",
        "//vendor/golang.org/x/net/http2",
        "//vendor/golang.org/x/oauth2",
        "//vendor/google.golang.org/api/googleapi/transport",
        "//vendor/google.golang.org/api/internal",
        "//vendor/google.golang.org/api/option",
        "//vendor/google.golang.org/api/transport/cert",
        "//vendor/google.golang.org/api/transport/http/internal/propagation",
        "//vendor/google.golang.org/api/transport/internal/dca",
    ],
)
