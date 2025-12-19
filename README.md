# HFT-Interview-Prep

<!--toc:start-->
- [HFT-Interview-Prep](#hft-interview-prep)
  - [Operating Systems/Low-level Knowledge:](#operating-systemslow-level-knowledge)
  - [Networking:](#networking)
  - [DSA/Algo Interview Prep:](#dsaalgo-interview-prep)
  - [Language Specifics:](#language-specifics)
  - [System Design:](#system-design)
  - [Mix of All/Other Resources:](#mix-of-allother-resources)
<!--toc:end-->

Guide to prepare for HFT interviews (SWEs) - **WIP**, will continue to add as I am finding new resources myself.

## Operating Systems/Low-level Knowledge:

  Reading:
  1. Operating Systems: Three Easy Pieces - https://pages.cs.wisc.edu/~remzi/OSTEP/
  2. Algorithmica / HPC - https://en.algorithmica.org/hpc/ (AMAZING resource)
  3. What Every Programmer Should Know About Memory - https://people.freebsd.org/~lstewart/articles/cpumemory.pdf
  4. Performance book: https://book.easyperf.net/perf_book + https://github.com/dendibakh/perf-ninja (do the labs and watch vids after reading book)
  5. Inside The Machine - a more in-depth book about CPU hardware.
  6. Linux internals - https://0xax.gitbooks.io/linux-insides/content/.


  Watching:
  1. CppCon 2017: Carl Cook “When a Microsecond Is an Eternity: High-Performance Trading Systems in C++” - https://www.youtube.com/watch?v=NH1Tta7purM (Goated)
  2. Trading at light speed: designing low latency systems in C++ - David Gross - Meeting C++ 2022 - https://www.youtube.com/watch?v=8uAW5FQtcvE (Good watch)

  Activities:
  1. https://highload.fun/ (mess around with this to learn optimisation techniques)


## Networking:

  1. TCP/IP Illustrated - has all the networking knowledge needed.
  2. Learn eBPF - (https://github.com/eunomia-bpf/bpf-developer-tutorial?tab=readme-ov-file).
  3. io_uring - https://unixism.net/2020/04/io-uring-by-example-part-1-introduction/ + https://unixism.net/loti/


## DSA/Algo Interview Prep:

  Reading:
  1. Competitive Programmer’s Handbook - https://cses.fi/book/book.pdf (short & sweet)
  2. Introduction to Algorithms - N/A (long, but whatever knowledge you need to consolidate from the CP handbook read specific chapters & answer qs)
  3. Data Structures in Practice: https://github.com/djiangtw/data-structures-in-practice-public/tree/main (practical DS knowledge)

  Doing:
  1. Neetcode.io -  https://neetcode.io/practice (Do the neetcode 150)
  2. Leetcode - https://leetcode.com/ (obvious but needed, do contests on weekends to build up the skill to solve qs under time pressure)
  3. CSES Problem set - https://cses.fi/problemset/list (Harder than LC but will make you better)


## Language Specifics:

C++: (maybe outta date idk)

  1. Learn CPP dot com - https://www.learncpp.com/ (Really good intro to cpp)
  2. Effective Modern C++ - https://www.amazon.co.uk/Effective-Modern-Specific-Ways-Improve/dp/1491903996
  3. Optimizing software in C++ - https://www.agner.org/optimize/optimizing_cpp.pdf
  4. C++ High Performance - https://www.amazon.com/High-Performance-Master-optimizing-functioning/dp/1839216549
  5. https://rigtorp.se/ - Good cpp focused blog.

Rust (For crypto-focused HFTs):

  1. https://rust-book.cs.brown.edu/title-page.html - Intro to Rust book
  2. https://github.com/rust-lang/rustlings  - Small Rust challenges to get used to the language.
  3. https://rust-lang.github.io/async-book/part-guide/intro.html - Async Rust guide (Also read Tokio docs + watch
Jon Gjengset: Decrusting tokio crate on YT).
  4. https://rust-unofficial.github.io/patterns/intro.html - Design patterns.
  5. https://nnethercote.github.io/perf-book/title-page.html - Rust perf book.
  6. https://marabos.nl/atomics/ - low lvl stuff.
  7. https://doc.rust-lang.org/nomicon/ - unsafe topics in Rust.
  8. https://rust-unofficial.github.io/too-many-lists/index.html - examples using all of above.
  9. https://os.phil-opp.com - Great blog series on creating an OS in rust.

## System Design:

  Reading:
  1. System Design Interview By Alex Lu - (Good, will help a bit long tho)

  Watching
  1. Grokking Modern System Design Interview - Educative.io (Can finish it quite quickly, pair that with practising random cases with a friend)


## Mix of All/Other Resources:

  Reading:
  1. Developing High-Frequency Trading Systems - https://www.amazon.co.uk/Developing-High-Frequency-Trading-Systems-high-frequency/dp/1803242817
  2. Ace the Trading Systems Developer Interview (C++ Edition) By Dennis Thompson - (Good for quick interview prep to brush up on C++ trivia etc, not a resource to rely on but will help if you forget some language-specific stuff + OS/Networking qs)

  Doing:
  1. No better way to learn than to build your own projects focused on HFT i.e. Order Book implementation, order management system, your own MM bot etc.

