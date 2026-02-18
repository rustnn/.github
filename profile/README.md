## RustNN

This is the rustnn project, organized into several repositories.

Start by reading https://github.com/rustnn/rustnn-workspace/blob/main/README.md and deep-dive

- rustnn-workspace : contains all repositories as sub repos, to work in a single, agentic-friendly space
- rustnn : main project, Rust implementation of WebNN
- rustnnpt : JS shim to pull WebNN WPT conformance tests and run them against RustNN to build https://rustnn.github.io/rustnnpt/
- pywebnn : Python bindings for rustnn
- webnn-onnx-utils : shared ONNX <-> WebNN conversion utilities
- webnn-graph : A WebNN DSL to serialized/deserialize WebNN graphs
- trtx-rs: Rust bindings to TensorRT-RTX
- search-bikeshed : search CLI for Bikeshed files (.bs) built for AI Coding agents
