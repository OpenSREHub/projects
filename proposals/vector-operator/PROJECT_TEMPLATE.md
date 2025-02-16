# Vector Operator

## Overview

A Kubernetes operator that simplifies the deployment and management of Vector observability pipelines in your Kubernetes cluster. This operator enables declarative configuration of Vector agents and data pipelines, making it easier to collect, transform, and forward observability data.

## Repository URL

[GitHub Repository](https://github.com/zcentric/vector-operator/)

## Features

The Vector Operator provides three custom resources:

- Vector: Manages the deployment of Vector agents (DaemonSet) in your cluster
- VectorAggregator: Manages the deployment of Vector aggregators (Deployment) in your cluster
- VectorPipeline: Defines observability data pipelines with sources, transforms, and sinks

### Key features:

- Declarative configuration of Vector instances
- Support for both agent (per-node) and aggregator (centralized) deployment type
- Pipeline management with support for multiple sources, transforms, and sinks
- Kubernetes-native deployment and management
- Automatic configuration updates and reconciliation
- Allows teams to manage their own VectorPipeline and it's merged into a central config
- The VectorPipeline is tested before merge to make sure the config is valid

## Installation & Usage

See repo for helm chart

## Contributing

Link to the `CONTRIBUTING.md` file for guidelines on how to contribute.

## License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
