# Prow Configuration

Core Prow component configuration is managed by the `config` package and stored in the [`Config` struct](https://godoc.org/github.com/jenkins-x/lighthouse/pkg/prow/config#Config). If a configuration guide is available for a component it can be found in the [`/prow/cmd`](/prow/cmd) directory. See [`jobs.md`](/prow/jobs.md) for a guide to configuring ProwJobs.
Configuration for plugins is handled and stored separately. See the [`plugins`](/prow/plugins) package for details.
