java_library(
    name = "jacoco_internal",
    srcs = glob([
        "org.jacoco.core/src/org/jacoco/core/**/*.java",
    ]),
    javacopts = [
        "-Xep:EqualsHashCode:WARN",
    ],
    deps = [
        "@jazzer_ow2_asm//:asm",
        "@jazzer_ow2_asm//:asm_commons",
        "@jazzer_ow2_asm//:asm_tree",
    ],
    visibility = ["//visibility:public"],
)
