load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "protolazy",
    srcs = [
        "bufferreader.go",
        "lazy.go",
        "pointer_unsafe.go",
    ],
    importmap = "k8s.io/cloud-provider-gcp/vendor/google.golang.org/protobuf/internal/protolazy",
    importpath = "google.golang.org/protobuf/internal/protolazy",
    visibility = ["//vendor/google.golang.org/protobuf:__subpackages__"],
    deps = [
        "//vendor/google.golang.org/protobuf/encoding/protowire",
        "//vendor/google.golang.org/protobuf/runtime/protoiface",
    ],
)
