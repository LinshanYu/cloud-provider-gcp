load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "cipher_suites.go",
        "doc.go",
        "tlsutil.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/go.etcd.io/etcd/pkg/tlsutil",
    importpath = "go.etcd.io/etcd/pkg/tlsutil",
    visibility = ["//visibility:public"],
)
