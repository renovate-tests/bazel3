# this commit should be updated to a new commit
go_repository(
    name = "org_golang_x_crypto",
    commit = "ccddf3741a0cfcee0a62d34c18c2c5417a3761af",
    importpath = "golang.org/x/crypto",
)

# this commit should be updated to a versioned tag
go_repository(
    name = "com_github_pkg_errors",
    commit = "ffb6e22f01932bf7ac35e0bad9be11f01d1c8685",
    importpath = "github.com/pkg/errors",
)

# this tag version should be updated
go_repository(
    name = "com_github_prometheus_prometheus",
    tag = "v2.6.1",
    importpath = "github.com/prometheus/prometheus",
)

# should find a new semantic git tag
git_repository(
    name = "build_bazel_rules_nodejs",
    remote = "https://github.com/bazelbuild/rules_nodejs.git",
    tag = "0.1.0",
)

# this http archive should be updated to a new release
http_archive(
    name = "io_bazel_rules_docker",
    url = "https://github.com/bazelbuild/rules_docker/archive/v0.7.0.tar.gz",
    strip_prefix = "rules_docker-0.5.1",
    sha256 = "aed1c249d4ec8f703edddf35cbe9dfaca0b5f5ea6e4cd9e83e99f3b0d1136c3d",
)
