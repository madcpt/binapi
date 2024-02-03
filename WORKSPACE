workspace(name = "binapi")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Makes @boost available for use: For example, add `@boost//:algorithm` to your deps.
# For more, see https://github.com/nelhage/rules_boost and https://www.boost.org
http_archive(
    name = "com_github_nelhage_rules_boost",
    url = "https://github.com/nelhage/rules_boost/archive/98bdaa9155c32a9b7aed15a2e6c33c90a2f6840c.tar.gz",
    strip_prefix = "rules_boost-98bdaa9155c32a9b7aed15a2e6c33c90a2f6840c",
)
load("@com_github_nelhage_rules_boost//:boost/boost.bzl", "boost_deps")
boost_deps()
