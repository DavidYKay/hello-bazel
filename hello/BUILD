package(default_visibility = ["//visibility:public"])

load("@rules_cc//cc:defs.bzl", "cc_binary", "cc_library", "cc_test")
load("@io_bazel_rules_d//d:d.bzl", "d_binary")

#c_library(
#    name = "hello-lib",
#    srcs = ["hello-lib.c"],
#    hdrs = ["hello-lib.h"],
#)

#cc_binary(
#    name = "hello-cpp",
#    srcs = ["hello.cpp"],
#    #deps = [":hello-lib"],
#)

config_setting(
    name = "foobar",
    values = {"define": "foo=bar"},
)

d_binary(
    name = "hello-d",
    srcs = ["hello.d"],
)
