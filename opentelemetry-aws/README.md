# OpenTelemetry AWS

![OpenTelemetry — An observability framework for cloud-native software.][splash]

[splash]: https://raw.githubusercontent.com/open-telemetry/opentelemetry-rust/main/assets/logo-text.png

| Status        |           |
| ------------- |-----------|
| Stability     | beta      |
| Owners        | [Jonathan Lee](https://github.com/jj22ee) |

Additional types for exporting [`OpenTelemetry`] data to AWS.

[![Crates.io: opentelemetry-aws](https://img.shields.io/crates/v/opentelemetry-aws.svg)](https://crates.io/crates/opentelemetry-aws)
[![Documentation](https://docs.rs/opentelemetry-aws/badge.svg)](https://docs.rs/opentelemetry-aws)
[![LICENSE](https://img.shields.io/crates/l/opentelemetry-aws)](./LICENSE)
[![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust-contrib/workflows/CI/badge.svg)](https://github.com/open-telemetry/opentelemetry-rust-contrib/actions?query=workflow%3ACI+branch%3Amain)
[![Slack](https://img.shields.io/badge/slack-@cncf/otel/rust-brightgreen.svg?logo=slack)](https://cloud-native.slack.com/archives/C03GDP0H023)

## Overview

[`OpenTelemetry`] is a collection of tools, APIs, and SDKs used to instrument,
generate, collect, and export telemetry data (metrics, logs, and traces) for
analysis in order to understand your software's performance and behavior. This
crate provides additional propagators and exporters for sending telemetry data
to AWS's telemetry platform.

## Supported component

Currently, this crate only supports `XRay` propagator and `Xray` ID Generator. Contributions are welcome.

[`OpenTelemetry`]: https://crates.io/crates/opentelemetry
