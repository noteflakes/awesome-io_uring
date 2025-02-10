# Awesome io_uring [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A categorized collection of awesome io_uring resources, libraries and tools.

Contributions and suggestions are always welcome! Please take a look at the
[contribution guidelines and quality
standard](https://github.com/ciconia/awesome-io_uring/blob/master/CONTRIBUTING.md)
first.

Thanks to all
[contributors](https://github.com/ciconia/awesome-io_uring/graphs/contributors),
you're awesome and this project wouldn't be possible without you!

* [Awesome io_uring](#awesome-io_uring)
  * [Documentation](#documentation)
  * [Blog posts](#blog-posts)
  * [Videos](#videos)
  * [C/C++](#cc)
  * [Go](#go)
  * [Java](#java)
  * [Lua](#lua)
  * [.NET](#net)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Rust](#rust)
  * [Software](#software)
* [Other Awesomeness](#other-awesomeness)
  * [Related lists](#related-lists)

## Documentation

* [io_uring manpage](https://www.mankier.com/7/io_uring)
* [Lord of the io_uring](https://unixism.net/loti/) - a guide to using io_uring

## Blog posts

(Ordered by stamp descending)

* 2023-04 [Why you should use io_uring for network I/O](https://developers.redhat.com/articles/2023/04/12/why-you-should-use-iouring-network-io)
* 2023-02 [io_uring and networking in 2023](https://github.com/axboe/liburing/wiki/io_uring-and-networking-in-2023)
* 2022-03 [IO_uring Gets New Features & Speed-Ups With Linux 5.18](https://www.phoronix.com/scan.php?page=news_item&px=Linux-5.18-IO_uring)
* 2022-03 [Put an io_uring on it: Exploiting the Linux Kernel](https://www.graplsecurity.com/post/iou-ring-exploiting-the-linux-kernel)
* 2022-02 [Missing Manuals - io_uring worker pool](https://blog.cloudflare.com/missing-manuals-io_uring-worker-pool/)
* 2021-12 [Zero-copy network transmission with
  io_uring](https://lwn.net/Articles/879724/)
* 2021-10 [Stupid tricks with io_uring: a server that does zero syscalls per
  request](https://wjwh.eu/posts/2021-10-01-no-syscall-server-iouring.html)
* 2021-06 [io_uring is not an event
  system](https://despairlabs.com/posts/2021-06-16-io-uring-is-not-an-event-system/)
* 2021-05 [Using io_uring to make a high-performance... finger server](https://drewdevault.com/2021/05/24/io_uring-finger-server.html)
* 2021-03 [I made a file copy thing](https://wheybags.com/blog/wcp.html)
* 2020-05 [Notes on io-uring](https://boats.gitlab.io/blog/post/io-uring/)
* 2020-05 [How io_uring and eBPF Will Revolutionize Programming in
  Linux](https://www.scylladb.com/2020/05/05/how-io_uring-and-ebpf-will-revolutionize-programming-in-linux/)
* 2020-04 [io_uring by
  example](https://unixism.net/2020/04/io-uring-by-example-article-series/)
* 2019-01 [Ringing in a new asynchronous I/O
  API](https://lwn.net/Articles/776703/)

## Videos

* 2022-06 [What's new with io_uring?](https://youtu.be/v--rVT4RsCE?t=2045) ([Slides](https://kernel.dk/axboe-kr2022.pdf))

## C/C++

* [ioucontext](https://github.com/pallas/ioucontext) - A coöperative
  multitasking framework based on `liburing` and `libucontext`.
* [libfev](https://github.com/patrykstefanski/libfev) - A library for events and
  fibers
* [liburing](https://github.com/axboe/liburing/) - wrapper lib for io_uring by
  [io_uring's author](https://github.com/axboe)
* [PhotonLibOS](https://github.com/alibaba/PhotonLibOS) - a high-efficiency LibOS framework, based on a set of carefully selected C++ libs.
* [xynet](https://github.com/xuanyi-fu/xynet) - network library based on
  io_uring and C++20 coroutine

## Go

* [go-uring](https://github.com/godzie44/go-uring) - The io_uring library and
  runtime for GO

## Java

* [io_uring-java](https://github.com/ChinaXing/io_uring-java) - Java binding for
  io_uring
* [Jliburing](https://github.com/Sammers21/Jliburing) - Java binding for
  liburing and io_uring

## Lua

* [Luring](https://github.com/thislight/luring) - a callback-style interface for
  Lua to io_uring

## .NET

* [IoUring](https://github.com/tkp1n/IoUring) - `io_uring` wrapper for C# / .NET

## Python

* [Liburing](https://github.com/YoSTEALTH/Liburing) - a Python + CFFI wrapper
  around the liburing C library

## Ruby

* [io-event](https://github.com/socketry/io-event/) - Fiber scheduler for Ruby 3.0
* [polyphony](https://github.com/digital-fabric/polyphony) - Fiber-based
  concurrency for Ruby using io_uring

## Rust

* [glommio](https://github.com/DataDog/glommio) - a Cooperative Thread-per-Core
  crate for Rust & Linux based on io_uring
* [io-uring](https://github.com/tokio-rs/io-uring) - The io_uring library for
  Rust
* [Monoio](https://github.com/bytedance/monoio) - a thread-per-core Rust runtime
  with io_uring
* [nuclei](https://github.com/vertexclique/nuclei) - Proactive IO & Runtime system
* [ringbahn](https://github.com/ringbahn/ringbahn) - safe bindings to io_uring
* [rio](https://github.com/spacejam/rio) - pure rust io_uring library, built on
  libc, thread & async friendly, misuse resistant
* [trale](https://github.com/hexagonal-sun/trale) - a tiny rust async linux executor
  using an io_uring-based reactor

## Software

* [Cachegrand](https://github.com/danielealbano/cachegrand) - an open-source
  fast, scalable and secure Key-Value
* [Dragonfly](https://github.com/dragonflydb/dragonfly) - A modern replacement for Redis and Memcached
* [plocate](https://plocate.sesse.net/) - a much faster `locate` using io_uring
* [Short-circuit](https://github.com/3541/short-circuit) - High-performance web
  server for Linux, built on io_uring
* [wcp](https://github.com/wheybags/wcp) - Copy files very fast using io_uring

# Other Awesomeness

## Related lists

Other amazingly awesome lists can be found in the
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
list.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Sharon Rosner](http://github.com/ciconia) has
waived all copyright and related or neighboring rights to this work.
