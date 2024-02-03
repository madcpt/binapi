cc_library(
    name = "binapi",
    hdrs = glob(["include/binapi/*.hpp"]),
    srcs = glob(["src/*.cpp"]),
    visibility = ["//visibility:public"],
    includes = ["include"],  # Specify the root include directory
    deps = [
        "@boost//:multiprecision",
        "@boost//:variant",
        "@boost//:asio_ssl",
        "@boost//:beast",
        "@boost//:callable_traits",
        "@boost//:format",
    ],
)
