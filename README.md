# HFT Digital Twin

A low-latency trading system simulation platform combining Rust systems programming, C++ performance engineering, and AI-based latency prediction.


## Project Overview

HFT Digital Twin simulates a high-frequency trading environment where market events are generated, processed, measured, and analyzed.

The project demonstrates:

- Low latency event processing
- Rust and C++ performance comparison
- Automated benchmarking
- Machine learning based latency prediction


## Architecture


Market Events

        |
        v

+----------------+
| Rust Engine    |
| Event System   |
+----------------+

        |
        v

Latency Dataset

        |
        v

+----------------+
| Python AI      |
| XGBoost Model  |
+----------------+

        |
        v

Prediction Report


        |
        v

+----------------+
| C++ Engine     |
| Benchmark      |
+----------------+



## Components


### Rust Engine

Features:

- High performance event processing
- Optimized memory handling
- Benchmark generation
- Release mode performance testing


### C++ Low Latency Engine

Features:

- Preallocated memory
- Cache-friendly processing
- Optimized event loop
- High throughput benchmark


### Python AI Layer

Features:

- Latency prediction model
- XGBoost training pipeline
- Model inference system



## Performance Benchmark

Optimized benchmark results:


Engine          Events/sec

C++             262,965,238

Rust            46,717,770



## How To Run


### Rust Engine

cd rust-engine

cargo run --release



### C++ Engine

cd cpp-engine

g++ -O3 cpp-engine/main.cpp -o hft_engine

./hft_engine



### Benchmark Analyzer

python3 benchmarks/analyze_benchmark.py



## Technologies Used

- Rust
- C++
- Python
- XGBoost
- Git
- Linux
- Performance Benchmarking



## Engineering Concepts Demonstrated

- Low latency system design
- Memory optimization
- Throughput measurement
- Event-driven architecture
- ML inference pipeline
- Performance analysis
