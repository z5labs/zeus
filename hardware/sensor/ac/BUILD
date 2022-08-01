load("@bazel_latex//:latex.bzl", "latex_document")

latex_document(
    name = "circuit_diagram",
    srcs = glob([
        "*.tex",
    ]) + [
      "@bazel_latex//packages:tikz",
      "@texlive_texmf__texmf-dist__tex__generic__circuitikz",
      "@texlive_texmf__texmf-dist__tex__latex__circuitikz",
    ],
    main = "circuit_diagram.tex",
)