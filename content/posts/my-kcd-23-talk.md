---
title: "My KCD Shenzhen '23 Talk (中文)"
description: "My talk 'Wasm Meets Go' at KCD 23 at Shenzhen"
date: 2024-01-02 00:00:00 +0000 UTC
authorlink: "https://twitter.com/jiaiao_zhou"
tags: ["wasm", "go", "wasi"]
---

I recently gave a talk in Chinese at [KCD Shenzhen 23](https://community.cncf.io/events/details/cncf-kcd-shenzhen-presents-kcd-shenzhen-2023/) about the present and future of Go + Wasm, titled _"Go Meets Wasm: Harnessing the Power of Wasm Components with Go"_. The talk is in Chinese, but the slides are in English.

Here is the abstract:

> Go is loved by developers for its simplicity, concurrency and efficiency. While Go’s 1.21 release brought WASI Preview 1 support into the fold, it hasn’t yet kept up with the evolving Wasm Component Model proposal. This talk explores how to bridge the gap by using several Go tools to build Wasm components suited for cloud-native and serverless workloads, including - Go and TinyGo compilers producing Wasm binaries with WASI. - wit-bindgen, a code generator for which the speaker built Go support. - wasi-cloud-core, a WASI proposal to standardize cloud APIs like key/value and messaging. The audience will learn how to use Go to build Wasm components that are able to do service invocations, database connections and interactions with cloud provider APIs. This talk will show how to package and deploy these components using Kubernetes. This talk concludes with a discussion on areas for improvement to enhance the Go developer experience in building Wasm Cloud-Native applications.

{{< youtube Q7BIJX7gTGg >}}

You can find the slides [here](https://docs.google.com/presentation/d/e/2PACX-1vTEheVCztS-q7fp1yg4mTVHmeZ6Ij3v7Li1orQy-wV4dm3v7h_USS-v9zJykpbYPK26DUDWgL-mgUkH/pub?start=false&loop=false&delayms=3000&slide=id.g2636dde8ba7_0_0)
