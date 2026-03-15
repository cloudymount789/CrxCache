# CrxCache

> A high-performance, thread-safe in-memory caching library implemented in C++11/14.

## 📖 Description
CrxCache is designed for low-latency scenarios, supporting multiple eviction strategies like **LRU, LFU, and ARC**. By leveraging **cache sharding** to minimize lock contention, it provides exceptional throughput in high-concurrency environments, making it ideal for performance-critical backend services.

## ✨ Key Features
* **Multi-Strategy**: Support for LRU, LFU, and the advanced ARC algorithm.
* **Concurrency-Optimized**: Granular locking via sharding for high QPS.
* **Header-only / Easy Integration**: Minimal dependencies.
* **Thread-Safe**: Safe for multi-threaded production environments.

## 🚀 Quick Start

```cmd
mkdir build && cd build
cmake ..
make
./main
```
