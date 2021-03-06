---
title: "Enhancing DataRaceBench for Evaluating DataRace Detection Tools"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'DataRaceBench is a dedicated benchmark suite to evaluate tools aimed to find data race bugs in OpenMP programs. Since its initial release in 2017, DataRaceBench has been widely used by tool developers to find the strengths and limitations of their tools. The results also provide an apple-to-apple comparison of the state-of-the-art of data race detection tools. In this paper, we discuss our latest efforts to enhance DataRaceBench. In particular, we have added support for Fortran language and some of the newest OpenMP 5.0 language features. We have also added new kernels representing new patterns from literature and other benchmarks (e.g., NAS Parallel Benchmark). To reduce duplicated code patterns in the benchmark suite, we have designed a distance-based code similarity analysis, combining both static and dynamic code features. Finally, we dockerize tools and streamline the entire benchmarking process to quickly generate a dashboard showing the state-of-the-art of data race detection of OpenMP programs. The enhanced DataRaceBench is released as v 1.3.0, with 222 newly added benchmarks. 56 of them are in C, and the remaining 166 are in Fortran, reproducing the C programs’ nature. Our experiments show that this new version can spot more limitations of the current data race detection tools, with significantly reduced user efforts needed to run experiments.'
date: 2010-11-09
venue: 'International Workshop on Software Correctness for HPC Applications (Correctness) SC20'
paperurl: 'https://conferences.computer.org/scwpub/pdfs/Correctness2020-7w4N9SxLsNAh5SqG4rrKiF/104400a020/104400a020.pdf'
citation: 'Gaurav Verma, Yaying Shi, Chunhua Liao, Barbara Chapman, and Yonghong Yan. (2010). &quot;Enhancing DataRaceBench for Evaluating DataRace Detection Tools.&quot; <i>International Workshop on Software Correctness for HPC Applications (Correctness) SC20</i>. 1(2).'
---
DataRaceBench is a benchmark suite designed to systematically and quantitatively evaluate the effectiveness of data race detection tools. It includes a set of microbenchmarks with and without data races. Parallelism is represented by OpenMP directives. OpenMP is a popular parallel programming model for multi-threaded applications.

Note that some microbenchmarks use OpenMP 4.5 and 5.0 features. You may need a recent OpenMP compiler to compile them.

DataRaceBench also comes with an evaluation script (check-data-races.sh). The script can be used to evaluate the tools Helgrind, Archer, Thread Sanitizer, Intel Inspector, and Coderrect Scanner. In addition a parameterized test harness (scripts/test-harness.sh) is available which allows to provide a number of different parameters for the evaluation. The test harness is used by the evaluation script with some pre-defined values.

[Download paper here](https://conferences.computer.org/scwpub/pdfs/Correctness2020-7w4N9SxLsNAh5SqG4rrKiF/104400a020/104400a020.pdf)

Recommended citation: Gaurav Verma, Yaying Shi, Chunhua Liao, Barbara Chapman, and Yonghong Yan. (2010). "Enhancing DataRaceBench for Evaluating DataRace Detection Tools." <i>International Workshop on Software Correctness for HPC Applications (Correctness) SC20</i>. 1(2).
