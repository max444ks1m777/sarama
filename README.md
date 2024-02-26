# sarama
Sarama is an MIT-licensed Go client library for [Apache Kafka](https://kafka.apache.org/).

## Getting started

- Mocks for testing are available in the [mocks](./mocks) subpackage.
- The [examples](./examples) directory contains more elaborate example applications.
- The [tools](./tools) directory contains command line tools that can be useful for testing, diagnostics, and instrumentation.

## Compatibility and API stability

Sarama provides a "2 releases + 2 months" compatibility guarantee: we support
the two latest stable releases of Kafka and Go, and we provide a two month
grace period for older releases. However, older releases of Kafka are still likely to work.

Sarama follows semantic versioning and provides API stability via the standard Go
[module version numbering](https://go.dev/doc/modules/version-numbers) scheme.

A changelog is available [here](CHANGELOG.md).

## Contributing

- The [Kafka Protocol Specification](https://cwiki.apache.org/confluence/display/KAFKA/A+Guide+To+The+Kafka+Protocol) contains a wealth of useful information.
- For more general issues, there is [a google group](https://groups.google.com/forum/#!forum/kafka-clients) for Kafka client developers.
- If you have any questions, just ask!
