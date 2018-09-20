load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
http_archive(
    name = "io_bazel_rules_go",
    url = "https://github.com/bazelbuild/rules_go/archive/cbc1e32fba771845305f15e341fa26595d4a136d.zip",
    strip_prefix = "rules_go-cbc1e32fba771845305f15e341fa26595d4a136d",
    sha256 = "d02b1d8d11fb67fb1e451645256e58a1542170eedd6e2ba160c8540c96f659da",
)
http_archive(
    name = "bazel_gazelle",
    url = "https://github.com/bazelbuild/bazel-gazelle/archive/6d34b3ce6607023ed9626f42db1231df978332bd.zip",
    strip_prefix = "bazel-gazelle-6d34b3ce6607023ed9626f42db1231df978332bd",
    sha256 = "8b4c710c371dbbd132b46ea5cf15ab2d5aee265b78108c2bf62044f9629de3d6",
)
load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains")
go_rules_dependencies()
go_register_toolchains()
load("@bazel_gazelle//:deps.bzl", "gazelle_dependencies")
gazelle_dependencies()