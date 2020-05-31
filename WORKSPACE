load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "bazel_ebook",
    remote = "https://github.com/filmil/bazel-ebook",
    branch = "master",
)

load(
    "@bazel_ebook//build:repositories.bzl",
    "bazel_ebook_repositories",
)

bazel_ebook_repositories()

