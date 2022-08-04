load("@bazel_latex//:latex.bzl", "latex_document")

latex_document(
    name = "research",
    srcs = glob([
        "*.tex",
    ]) + [
      "@bazel_latex//packages:multicol",
    ],
    main = "research.tex",
) 