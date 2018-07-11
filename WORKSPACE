workspace(name = "workspacename")

git_repository(
	name = "build_bazel_rules_nodejs",
	remote = "https://github.com/bazelbuild/rules_nodejs.git",
	tag = "0.10.1", # check for the latest tag when you install
)

load("@build_bazel_rules_nodejs//:defs.bzl", "node_repositories")

node_repositories(package_json = ["//:package.json"])

print("AFTER LOADING WORKSPACE")