# Anomaly Detection
Anomaly detection service for streaming data. Anomaly detection employs multiple methods and approaches. It is able to connect to a particular uni- or multi-variate data stream and provide detected anomalies.

## Implemented Brokers
Plan:

* CSV
* Kafka

## Implemented Anomaly Detection Models

* Concept drift detectors (based on scikit-multiflow)
* Histogram based anomaly detection
* Hard-limits anomaly
* ADTK
    * ThresholdAD
    * QuantileAD
    * InterQuantileRangeAD
    *

## Development
For documentation [Read the Docs](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html#) is used. Rebuild documentation with running `make html` in directory `docs/`.