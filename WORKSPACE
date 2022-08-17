workspace(name = "zeus")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_latex",
    sha256 = "6007da2ea603a00a2f481e5683c722fbdd269c173d5e0d6c5d6f5f4d874a366e",
    strip_prefix = "bazel-latex-1.1.1",
    url = "https://github.com/ProdriveTechnologies/bazel-latex/archive/v1.1.1.tar.gz",
)

load("@bazel_latex//:repositories.bzl", "latex_repositories")

latex_repositories()