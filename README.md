# sarama

[![Go Reference](https://pkg.go.dev/badge/github.com/ihezebin/sarama.svg)](https://pkg.go.dev/github.com/ihezebin/sarama)
[![Build Status](https://travis-ci.org/Shopify/sarama.svg?branch=master)](https://travis-ci.org/Shopify/sarama)
[![Coverage](https://codecov.io/gh/Shopify/sarama/branch/master/graph/badge.svg)](https://codecov.io/gh/Shopify/sarama)

Sarama is an MIT-licensed Go client library for [Apache Kafka](https://kafka.apache.org/) version 0.8 (and later).

## Getting started

- API documentation and examples are available via [pkg.go.dev](https://pkg.go.dev/github.com/ihezebin/sarama).
- Mocks for testing are available in the [mocks](./mocks) subpackage.
- The [examples](./examples) directory contains more elaborate example applications.
- The [tools](./tools) directory contains command line tools that can be useful for testing, diagnostics, and instrumentation.

You might also want to look at the [Frequently Asked Questions](https://github.com/ihezebin/sarama/wiki/Frequently-Asked-Questions).

## Compatibility and API stability

Sarama provides a "2 releases + 2 months" compatibility guarantee: we support
the two latest stable releases of Kafka and Go, and we provide a two month
grace period for older releases. This means we currently officially support
Go 1.15 through 1.16, and Kafka 2.6 through 2.8, although older releases are
still likely to work.

Sarama follows semantic versioning and provides API stability via the gopkg.in service.
You can import a version with a guaranteed stable API via http://gopkg.in/Shopify/sarama.v1.
A changelog is available [here](CHANGELOG.md).

## Contributing

- Get started by checking our [contribution guidelines](https://github.com/ihezebin/sarama/blob/master/.github/CONTRIBUTING.md).
- Read the [Sarama wiki](https://github.com/ihezebin/sarama/wiki) for more technical and design details.
- The [Kafka Protocol Specification](https://cwiki.apache.org/confluence/display/KAFKA/A+Guide+To+The+Kafka+Protocol) contains a wealth of useful information.
- For more general issues, there is [a google group](https://groups.google.com/forum/#!forum/kafka-clients) for Kafka client developers.
- If you have any questions, just ask!
