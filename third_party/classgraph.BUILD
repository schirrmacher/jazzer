load("@rules_java//java:defs.bzl", "java_library")

java_library(
    name = "classgraph",
    srcs = glob([
        "src/main/java/io/github/classgraph/**/*.java",
        "src/main/java/nonapi/io/github/classgraph/**/*.java",
    ]),
    visibility = ["//visibility:public"],
)
