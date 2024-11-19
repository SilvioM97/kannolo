# kANNolo: Sweet and Smooth Approximate k-Nearest Neighbors Search

![kannolo](./kannolo.png)

## What is kANNolo

kANNolo is the first ANN library that supports dense and sparse vector representations made available on top of different similarity measures, e.g., euclidean distance and inner product. Moreover, it also supports vector quantization techniques, e.g., Product Quantization, on top of the indexing strategies implemented. These functionalities are managed through Rust traits, allowing shared behaviors to be handled abstractly. This abstraction ensures flexibility and facilitates an easy integration of new components.

The experimental analysis on public datasets shows that kANNolo achieves state-of-the-art performance in terms of speed-accuracy trade-off while allowing fast and easy prototyping, thus making kANNolo a valuable tool for advancing ANN research.
