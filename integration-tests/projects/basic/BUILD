cc_library(
    name = "foofunc",
    srcs = ["foo.h", "foo.cpp"]
)

cc_test(
    name = "foo_test",
    srcs = ["test.cpp"],
    deps = ["@googletest//:gtest_main",
            "foofunc",
	    "//support/gtest/include:lobster_gtest"]
)
