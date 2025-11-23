# Awesome Go [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome articles to learn Go.

## Contents
- [Awesome Go](#awesome-go)
- [Contents](#contents)
- [Language Features](#language-features)
- [Concurrency & Runtime](#concurrency--runtime)
- [System Design & Engineering](#system-design--engineering)
- [Performance & Optimization](#performance--optimization)
- [Project Organization & Architecture](#project-organization--architecture)
- [Learning Resources](#learning-resources)

## Language Features

### Go 1.24
- [Go 1.24: New map by Swiss Table](https://zhuanlan.zhihu.com/p/29295935067): Swiss Table and Golang new version of the map.

### Go 1.25
- [GO 1.25: True streaming marshal —— json/v2](https://mp.weixin.qq.com/s/pYlGeF1yBlIy07DDvsIzrw): A comparative experiment on streaming marshal between json/v1 and json/v2.
- [GO 1.25: Flight Recorder](https://mp.weixin.qq.com/s/F3ZgRIXW_2V0TnbBUlwAfg): Introduces Flight Recorder in Go 1.25, which captures the last few seconds of execution to locate performance bottlenecks with low overhead, suitable for production debugging.
- [GO 1.25: Green Tea GC](https://mp.weixin.qq.com/s/W75ulkZU06-zLdfj3F_a-w): Page-based marking improves cache locality; reduces GC time by 10–40% in some scenarios.

## Concurrency & Runtime

### GMP Scheduler
- [GMP1: What is GMP?](https://juejin.cn/post/7324931501926875170): Introducing GMP Basics.
- [GMP2: What does the Go program do when it starts??](https://juejin.cn/post/7327138554756857908): loading...

## System Design & Engineering

- [HTTP Client Timeout, Retry, and Resilience Patterns in Go](https://mp.weixin.qq.com/s/2v9A6CRjmyMoOK8vFJF5Ag): In-depth guide on HTTP client timeout control, retry strategies, idempotency guarantees, and performance optimization. Covers context propagation, exponential backoff, connection pool configuration, and sync.Pool memory reuse patterns.

## Performance & Optimization

- [Flight Recorder](#go-125-flight-recorder): Capture execution snapshots for performance bottleneck analysis with minimal overhead.
- [Green Tea GC](#go-125-green-tea-gc): Cache-friendly page-based marking for improved GC performance.

## Project Organization & Architecture

- [Organizing projects and defining names in Go](https://medium.com/inside-picpay/organizing-projects-and-defining-names-in-go-7f0eab45375d): Organize Go projects with domain-driven layers and concise, context-aware naming for maintainable, testable code.

## Learning Resources

### Books
- [Go language design and implementation](https://draven.co/golang/)

### Premium Columns
- [Go Language Project Development](https://learn.lianglianglee.com/%E4%B8%93%E6%A0%8F/Go%20%E8%AF%AD%E8%A8%80%E9%A1%B9%E7%9B%AE%E5%BC%80%E5%8F%91%E5%AE%9E%E6%88%98): Team norms are more important than individual skills.

### Recommended Resources

10 best Go resources in my bookmarks. Read just one and you're in good shape:

1. Go Concurrency Rocks: [https://concurrency.rocks](https://concurrency.rocks)
2. Go Cookbook: [https://go-cookbook.com](https://go-cookbook.com)
3. 100 Go Mistakes and How to Avoid Them: [https://100go.co](https://100go.co)
4. Practical Go Lessons: [https://practical-go-lessons.com](https://practical-go-lessons.com)
5. Common Performance Patterns: [https://goperf.dev/01-common-patterns/](https://goperf.dev/01-common-patterns/)
6. Practical Networking Patterns: [https://goperf.dev/02-networking/](https://goperf.dev/02-networking/)
7. Learn Go with Tests: [https://quii.gitbook.io/learn-go-with-tests](https://quii.gitbook.io/learn-go-with-tests)
8. Guide to Go Profiling, Tracing and Observability: [https://github.com/DataDog/go-profiler-notes/blob/main/guide/README.md](https://github.com/DataDog/go-profiler-notes/blob/main/guide/README.md)
9. Go Class: [https://youtube.com/playlist?list=PLoILbKo9rG3skRCj37Kn5Zj803hhiuRK6](https://youtube.com/playlist?list=PLoILbKo9rG3skRCj37Kn5Zj803hhiuRK6)
10. Go Roadmap: [https://roadmap.sh/golang](https://roadmap.sh/golang)

Bonus:

11. Go at VictoriaMetrics series: [https://victoriametrics.com/blog/categories/go-@-victoriametrics/](https://victoriametrics.com/blog/categories/go-@-victoriametrics/)
12. Go Practical Tips (by me): [https://github.com/func25/go-practical-tips/blob/main/tips.md](https://github.com/func25/go-practical-tips/blob/main/tips.md)
