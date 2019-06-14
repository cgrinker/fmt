cc_library(
    name="headers",
    visibility = ["//visibility:public"],
    includes=[
        "include"
    ],
    hdrs=glob([
        "include/**/*.h*",
    ]),
)

cc_library(
    name="fmt",
    visibility = ["//visibility:public"],
    srcs=glob([
        "src/**/*.c*"
    ]),
    deps = [
        ":headers"
    ]
)