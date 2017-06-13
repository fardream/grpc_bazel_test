load("@grpc//bazel:cc_grpc_library.bzl", "cc_grpc_library")

cc_grpc_library(
    name = "test",
    srcs = [ "test.proto" ],
    deps = [],
    proto_only = False,
    well_known_protos = "@com_google_protobuf//:well_known_protos",
    generate_mock = False,
    use_external = True
)
