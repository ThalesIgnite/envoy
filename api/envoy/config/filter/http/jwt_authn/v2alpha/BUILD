load("//bazel:api_build_system.bzl", "api_proto_library")

licenses(["notice"])  # Apache 2

api_proto_library(
    name = "jwt_authn",
    srcs = ["config.proto"],
    deps = [
        "//envoy/api/v2/route",
        "//envoy/config/filter/http/common/v1alpha:common",
    ],
)
