package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
)

go_binary(
    name = "kubeadm",
    srcs = ["kubeadm.go"],
    tags = ["automanaged"],
    deps = ["//cmd/kubeadm/app:go_default_library"],
)
