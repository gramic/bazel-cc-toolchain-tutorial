package(default_visibility = ["//visibility:public"])

filegroup(
    name = "all",
    srcs = glob(["**/*"]),
)

py_binary(
    name = "generate_emscripten_cache",
    srcs = ["generate_emscripten_cache.py"],
    data = [":transform"],  # a cc_binary which we invoke at run time
    deps = [],
)
