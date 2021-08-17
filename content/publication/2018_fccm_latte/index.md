---
title: 2018_fccm_latte
publication_types:
  - "1"
authors:
  - Jason Cong
  - Peng Wei
  - Cody Hao Yu
  - admin
abstract: "Modern FPGA chips feature abundant reconfigurable resources such as
  LUTs, FFs, BRAMs and DSPs. High-level synthesis (HLS) further advances users
  productivity in designing accelerators and scaling out the design quickly via
  fine-grain and coarse-grain pipelining and duplication to utilize on-chip
  resources. However, current HLS tools fail to consider data locality in the
  scaled-out design; this leads to a long critical path which results in a low
  operating frequency. In this paper we summarize the timing degradation
  problems to four common collective communication and computation patterns in
  HLS-based accelerator design: scatter, gather, broadcast and reduce. These
  widely used patterns scale poorly in one-to-all or all-to-one data movements
  between off-chip communication interface and on-chip storage, or inside the
  computation logic. Therefore, we propose the Latte microarchitecture featuring
  pipelined transfer controllers (PTC) along data paths in these patterns.
  Furthermore, we implement an automated framework to apply our Latte
  implementation in HLS with minimal user efforts. Our experiments show that
  Latte-optimized designs greatly improve the timing of baseline HLS designs by
  1.50x with only 3.2% LUT overhead on average, and 2.66x with 2.7% overhead at
  maximum."
draft: false
featured: false
tags:
  - fccm
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2021-08-17T09:14:43.992Z
---