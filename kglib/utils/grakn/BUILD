load("@io_bazel_rules_python//python:python.bzl", "py_library")
load("@pypi_dependencies//:requirements.bzl", "requirement")


py_library(
    name = "grakn",
    deps = [
        '//kglib/utils/grakn/test',
        '//kglib/utils/grakn/object',
        '//kglib/utils/grakn/synthetic',
        '//kglib/utils/grakn/type',
    ],
    visibility=['//visibility:public']
)