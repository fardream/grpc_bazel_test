bind(
    name = "grpc_cpp_plugin",
    actual = "@grpc//:grpc_cpp_plugin"
)
bind(
    name = "grpc++",
    actual = "@grpc//:grpc++"
)
bind(
    name = "grpc_lib",
    actual = "@grpc//:grpc++"
)

bind(
    name = "grpc++_codegen_proto",
    actual = "@grpc//:grpc++_codegen_proto"
)


new_local_repository(
    name = "grpc",
    path = "grpc",
    build_file = "grpc/BUILD"
)



new_local_repository(
    name = "com_google_protobuf",
    path = "grpc/third_party/protobuf",
    build_file = "grpc/third_party/protobuf/BUILD"
)

bind(
    name = "protobuf",
    actual = "@com_google_protobuf_cc//:protobuf"
)

bind(
    name = "protoc",
    actual = "@com_google_protobuf_cc//:protoc"
)

bind(
    name = "cc_wkt_protos",
    actual = "@com_google_protobuf_cc//:cc_wkt_protos"
)

bind(
    name = "protobuf_clib",
    actual = "@com_google_protobuf_cc//:protoc_lib"
)
bind(
    name = "protocol_compiler",
    actual = "@com_google_protobuf_cc//:protoc"
)

new_local_repository(
    name = "com_google_protobuf_cc",
    path = "grpc/third_party/protobuf",
    build_file = "grpc/third_party/protobuf/BUILD"
)



bind(
    name = "nanopb",
    actual = "//grpc/third_party/nanopb",
)

bind(
    name = "libssl",
    actual = "@boringssl//:ssl",
)

bind(
    name = "zlib",
    actual = "@submodule_zlib//:z",
)

bind(
    name = "protobuf",
    actual = "@com_google_protobuf//:protobuf",
)

bind(
    name = "protobuf_clib",
    actual = "@com_google_protobuf//:protoc_lib",
)

bind(
    name = "protocol_compiler",
    actual = "@com_google_protobuf//:protoc",
)

bind(
    name = "cares",
    actual = "@submodule_cares//:ares",
)

bind(
    name = "gtest",
    actual = "@submodule_gtest//:gtest",
)

bind(
    name = "benchmark",
    actual = "@submodule_benchmark//:benchmark",
)

bind(
    name = "gflags",
    actual = "@com_github_gflags_gflags//:gflags",
)

local_repository(
    name = "boringssl",
    path = "grpc/third_party/boringssl-with-bazel",
)

new_local_repository(
    name = "submodule_zlib",
    build_file = "grpc/third_party/zlib.BUILD",
    path = "grpc/third_party/zlib",
)

new_local_repository(
    name = "com_google_protobuf",
    build_file = "grpc/third_party/protobuf/BUILD",
    path = "grpc/third_party/protobuf",
)

new_local_repository(
    name = "submodule_gtest",
    build_file = "grpc/third_party/gtest.BUILD",
    path = "grpc/third_party/googletest",
)

local_repository(
    name = "com_github_gflags_gflags",
    path = "grpc/third_party/gflags",
)

new_local_repository(
    name = "submodule_benchmark",
    path = "grpc/third_party/benchmark",
    build_file = "grpc/third_party/benchmark.BUILD",
)

new_local_repository(
    name = "submodule_cares",
    path = "grpc/third_party/cares",
    build_file = "grpc/third_party/cares/cares.BUILD",
)
