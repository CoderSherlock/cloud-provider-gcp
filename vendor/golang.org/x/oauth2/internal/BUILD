load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "internal",
    srcs = [
        "doc.go",
        "oauth2.go",
        "token.go",
        "transport.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/golang.org/x/oauth2/internal",
    importpath = "golang.org/x/oauth2/internal",
    visibility = ["//vendor/golang.org/x/oauth2:__subpackages__"],
    deps = ["//vendor/golang.org/x/net/context/ctxhttp"],
)
