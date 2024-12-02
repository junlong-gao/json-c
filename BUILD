cc_library(
    name = "json-c",
    srcs = glob([
        "*.c",
        "*.h",
    ]),
    hdrs = ["json.h"],
    copts = [
        "-x",
        "c",
    ],
    includes = ["."],
    linkstatic = True,
    visibility = ["//visibility:public"],
)
