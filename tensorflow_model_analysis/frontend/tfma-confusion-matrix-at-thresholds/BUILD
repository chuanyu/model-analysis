licenses(["notice"])  # Apache 2.0

load("@io_bazel_rules_closure//closure:defs.bzl", "web_library")

package(
    default_visibility = [
        "//tensorflow_model_analysis/frontend:__subpackages__",
    ],
)

web_library(
    name = "lib",
    srcs = [
        "tfma-confusion-matrix-at-thresholds.html",
        "tfma-confusion-matrix-at-thresholds.js",
    ],
    path = "/tfma-confusion-matrix-at-thresholds",
    deps = [
        "@org_polymer",
        "@org_polymer_paper_tooltip",
    ],
)
