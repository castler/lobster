load("@lobster_dependencies//:requirements.bzl", "requirement")

py_library(
    name = "lobster",
    srcs = glob([
        "config/*.py",
        "html/*.py",
        "*.py",
    ]),
    imports = ["."],
    deps = [
        requirement("graphviz-py"),
    ],
)
