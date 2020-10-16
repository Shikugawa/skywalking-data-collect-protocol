load("@rules_proto//proto:defs.bzl", "proto_library")
load("@rules_cc//cc:defs.bzl", "cc_proto_library")

licenses(["notice"])  # Apache 2

proto_library(
  name = "tracing_protocol_proto_lib",
  srcs = ["Tracing.proto"],
  deps = ["//common:common_protocol_proto_lib"],
  visibility = ["//visibility:public"],
)

cc_proto_library(
  name = "tracing_protocol_cc_proto",
  deps = [":tracing_protocol_proto_lib"],
  visibility = ["//visibility:public"],
)
