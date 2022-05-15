workspace(name = "com_github_biojppm_rapidyaml")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "com_github_biojppm_c4core",
    init_submodules = True,
    # TODO(zaucy): Wait for c4core bazel support to be approved and switch to commit hash and official remote
    remote = "https://github.com/zaucy/c4core.git",
    branch = "feat/bazel-support",
)

http_archive(
    name = "doctest",
    strip_prefix = "doctest-2.4.8",
    urls = ["https://github.com/doctest/doctest/archive/refs/tags/v2.4.8.tar.gz"],
    sha256 = "",
)
