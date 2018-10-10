# Data Platform: NiFi Templates

This repository contains the templates of Apache NiFi flows, that implement ingestion logic for data platform.
The first flow exposes an HTTP endpoint that receives events in JSON format, validates them against Schema Registry, enriches them and streams to Kafka.