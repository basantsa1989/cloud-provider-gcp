load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "dynamic",
    srcs = [
        "interface.go",
        "scheme.go",
        "simple.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/k8s.io/client-go/dynamic",
    importpath = "k8s.io/client-go/dynamic",
    visibility = ["//visibility:public"],
    deps = [
        "//vendor/k8s.io/apimachinery/pkg/api/meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1:meta",
        "//vendor/k8s.io/apimachinery/pkg/apis/meta/v1/unstructured",
        "//vendor/k8s.io/apimachinery/pkg/runtime",
        "//vendor/k8s.io/apimachinery/pkg/runtime/schema",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer",
        "//vendor/k8s.io/apimachinery/pkg/runtime/serializer/json",
        "//vendor/k8s.io/apimachinery/pkg/types",
        "//vendor/k8s.io/apimachinery/pkg/watch",
        "//vendor/k8s.io/client-go/rest",
        "//vendor/k8s.io/client-go/util/consistencydetector",
        "//vendor/k8s.io/client-go/util/watchlist",
        "//vendor/k8s.io/klog/v2:klog",
    ],
)
