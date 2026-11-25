# deterministic-operations-telemetry-gateway

[![Status](https://img.shields.io/badge/Status-Incubating-blue)]()
[![Huawei Cloud](https://img.shields.io/badge/Huawei%20Cloud-Samples-red)]()
[![Scenario](https://img.shields.io/badge/Scenario-deterministic%20operations-success)](https://3ms.huawei.com/docs/docinfo/1300901382590492672?bookstackId=866760814559879168&gid=3591759&l=zh-cn&documentkind=&attachmentIdx=5)

A **centralized telemetry gateway** on Huawei Cloud, provisioned as infrastructure-as-code: an OpenTelemetry collector fleet runs inside a dedicated observability VPC, business VPCs connect privately through an Enterprise Router and push OTLP telemetry (traces / metrics / logs) to a single stable entry point. The gateway receives, batches, and routes the data to Application Performance Management (APM, traces), Application Operations Management (AOM, metrics), and Log Tank Service (LTS, logs).

## Overview

This repository is created from the huaweicloud-samples automated repository request workflow.

## Getting Started

Add setup, deployment, and verification steps here.

## Contributing

Please use pull requests and follow the repository review rules.

## License

This project is licensed under the MIT-0 license.

## Maintainers

CODEOWNERS: @Ferguson2211

## Feedback

Please use GitHub Issues: https://github.com/huaweicloud-samples/deterministic-operations-telemetry-gateway/issues
