load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
  name = 'emscripten_toolchain',
  url = 'https://github.com/kripken/emscripten/archive/1.37.22.tar.gz',
  build_file = '//:emscripten-toolchain.BUILD',
  strip_prefix = "emscripten-1.37.22",
)

http_archive(
  name = 'emscripten_clang',
  url = 'https://s3.amazonaws.com/mozilla-games/emscripten/packages/llvm/tag/linux_64bit/emscripten-llvm-e1.37.22.tar.gz',
  build_file = '//:emscripten-clang.BUILD',
  strip_prefix = "emscripten-llvm-e1.37.22",
)
