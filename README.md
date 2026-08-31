Python-Project-reuse-scripts
A core library of modular, highly cohesive Python scripts designed to eliminate boilerplate across data science, machine learning, and backend deployments. This repository centralizes common patterns into production-ready utilities, ensuring consistency and rapid prototyping across new repositories.

Key Modules & Capabilities

Data Processing (/data_utils): Memory-optimized loaders, vectorized Pandas/NumPy transformations, and automated ETL staging scripts for structured and unstructured data.

ML & Inference Pipelines (/ml_core): Standardized PyTorch training loops, dynamic hardware allocation (CUDA/MPS/CPU), inference wrappers for local LLMs/transformers, and scikit-learn evaluation metrics.

Infrastructure & System (/sys_ops): Thread-safe logging singletons, robust configuration parsers (YAML/JSON), environment validation, and concurrent file-handling operations.

API & Integration (/api_handlers): Retry-decorated request wrappers, pagination handlers, and payload formatting for external data ingestion.

Design Philosophy

Zero-Dependency First: Standard library used wherever possible; heavy dependencies (PyTorch, Pandas) are isolated to specific submodules.

Type Hinted: Full typing coverage for static analysis (mypy) and IDE autocompletion.

Drop-In Ready: Scripts are designed as decoupled modules that can be symlinked, cloned as submodules, or copy-pasted directly into new environments.
