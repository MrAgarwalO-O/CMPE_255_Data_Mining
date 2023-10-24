# Apache Beam Demonstration in Google Colab

An example of how to process a dataset using Apache Beam can be found in this Google Colab notebook. Various Apache Beam functionalities are demonstrated in the notebook, including:

1. Composite Transform
2. Pipeline I/O
3. Triggers
4. Windowing
5. ParDo

In addition to Apache Beam features, the notebook also contains exploratory data analysis (EDA) and data visualization steps.

## What is Apache Beam?

Apache Beam is an open-source, unified model for defining both batch and streaming data-parallel processing pipelines. Using one of the open-source Beam SDKs, you build a program that defines the pipeline. The pipeline is then executed by one of Beam’s supported distributed processing back-ends, which include Apache Flink, Apache Spark, and Google Cloud Dataflow.

Apache Beam provides a general approach to data processing with a series of abstractions:

1. **PCollection**: Represents a distributed dataset that can be processed in parallel.
2. **PTransform**: Represents a computation that transforms data.
3. **Pipeline**: Represents a series of transformations that can be applied to data.
4. **Pipeline I/O**: Represents reading from and writing to external systems.
5. **Windowing**: Represents dividing data into windows for processing.
6. **Triggers**: Represents conditions for when to produce results of windowed computations.

## References
https://beam.apache.org/documentation/ml/about-ml/ <br>
https://beam.apache.org/documentation/ml/overview/ <br>
https://beam.apache.org/documentation/transforms/python/elementwise/runinference-sklearn/
