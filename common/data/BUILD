load("@rules_proto//proto:defs.bzl", "proto_library")

package(default_visibility = ["//visibility:public"])

proto_library(
    name = "characters_storage_proto",
    srcs = ["characters_storage.proto"],
)

proto_library(
    name = "characters_client_proto",
    srcs = ["characters_client.proto"],
)

proto_library(
    name = "characters_service_proto",
    srcs = ["characters_service.proto"],
    deps = [":characters_client_proto"],
)