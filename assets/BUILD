genrule(
    name = "gen_assets",
    srcs = [
        "alert-triangle.svg",
        "award.svg",
        "check-square.svg",
        "chevron-down.svg",
        "external-link.svg",
        "link.svg",
        "menu.svg",
    ],
    outs = ["foo/gen/assets.py"],
    cmd = "$(location //util:mkassets) $(OUTS) $(SRCS)",
    tools = ["//util:mkassets"],
)

py_library(
    name = "assets",
    srcs = ["foo/gen/assets.py"],
    imports = [
        "foo",
    ],
    deps = [],
)
