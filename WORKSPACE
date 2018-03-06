http_archive(
    name = "build_bazel_rules_nodejs",
    url = "https://github.com/bazelbuild/rules_nodejs/archive/0.5.0.zip",
    strip_prefix = "rules_nodejs-0.5.0",
    sha256 = "06aabb253c3867d51724386ac5622a0a238bbd82e2c70ce1d09ee3ceac4c31d6",
)

load("@build_bazel_rules_nodejs//:defs.bzl", "node_repositories")
node_repositories(package_json = ["//:package.json"])

http_archive(
    name = "build_bazel_rules_typescript",
    url = "https://github.com/bazelbuild/rules_typescript/archive/0.11.0.zip",
    strip_prefix = "rules_typescript-0.11.0",
    sha256 = "ce7bac7b5287d5162fcbe4f7c14ff507ae7d506ceb44626ad09f6b7e27d3260b",
)
load("@build_bazel_rules_typescript//:defs.bzl", "ts_setup_workspace")
ts_setup_workspace()
