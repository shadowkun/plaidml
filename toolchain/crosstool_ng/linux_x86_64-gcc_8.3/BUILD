package(default_visibility = ["//visibility:public"])

filegroup(
    name = "compiler_files",
    srcs = [
        ":as",
        ":gcc",
        ":ld",
    ],
    tags = ["linux"],
)

filegroup(
    name = "linker_files",
    srcs = [
        ":ar",
        ":gcc",
        ":ld",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:all_files",
    ],
    tags = ["linux"],
)

filegroup(
    name = "ar",
    srcs = [
        "wrappers/ar",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:ar",
    ],
    tags = ["linux"],
)

filegroup(
    name = "as",
    srcs = [
        "wrappers/as",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:as",
    ],
    tags = ["linux"],
)

filegroup(
    name = "gcc",
    srcs = [
        "wrappers/gcc",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:gcc",
    ],
    tags = ["linux"],
)

filegroup(
    name = "ld",
    srcs = [
        "wrappers/ld",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:ld",
    ],
    tags = ["linux"],
)

filegroup(
    name = "nm",
    srcs = [
        "wrappers/nm",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:nm",
    ],
    tags = ["linux"],
)

filegroup(
    name = "objcopy",
    srcs = [
        "wrappers/objcopy",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:objcopy",
    ],
    tags = ["linux"],
)

filegroup(
    name = "objdump",
    srcs = [
        "wrappers/objdump",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:objdump",
    ],
    tags = ["linux"],
)

filegroup(
    name = "strip",
    srcs = [
        "wrappers/strip",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:strip",
    ],
    tags = ["linux"],
)

filegroup(
    name = "all_files",
    srcs = [
        ":ar",
        ":as",
        ":gcc",
        ":ld",
        ":nm",
        ":objcopy",
        ":objdump",
        ":strip",
        "@crosstool_ng_linux_x86_64_gcc_8.3//:all_files",
    ],
    tags = ["linux"],
)
