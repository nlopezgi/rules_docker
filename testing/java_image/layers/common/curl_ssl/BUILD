load("@io_bazel_rules_docker//docker/toolchain_container:toolchain_container.bzl", "language_tool_layer")

package(default_visibility = ["//visibility:public"])

language_tool_layer(
    name = "curl_ssl_ltl",
    base = "//images/build/base_tool:tool_base_image.tar",
)
