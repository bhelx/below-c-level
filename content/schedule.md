---
title: "Schedule"
date: 2023-02-10T11:19:01-06:00
draft: false
---

# Upcoming

## 2023-12-05T18:00:00-06:00 - Dominique Saulet - WebAssembly Unpacked: A Guide to Wasm

Perhaps you’ve heard of WebAssembly (Wasm) and all of the associated refrains: virtual Instruction Set Architecture (ISA), web standard, stack-based virtual machine, fantasy computer, and compilation target. Perhaps you’ve been told of its feature set: sandboxed security, highly performant and portable byte code format, and perhaps even, you’ve heard the prophecies: the holy grail of 'write once, run anywhere' (sorry Java), the common denominator for all compute, a bridge from languages, high and low, to platforms in the cloud and off to the far edge. But the truth, you see, is that Wasm is here. It’s all around you. Even now, in your browser, in your streaming services, in your serverless functions, extending your SaaS platforms, and running your AI models. And so, together, let’s unpack this alien tech and all of the arcane words that describe it, bit by bit, byte by byte, to discover what strange mechanisms make it tick, and what it means for the future.

# Archive

## 2023-11-07T18:00:00-06:00 - Lightning Talks

* Devin Villegas (Software Eng. @ Netflix) will discuss formal methods
* Benjamin Eckel will talk about a new Wasm runtime he's working on

<iframe width="560" height="315" src="https://www.youtube.com/embed/qKwQ7k7kwko?si=T1hdKwYtEc7U_sd2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-10-03T18:00:00-06:00 - Austin Clements: Reversing SEGA ROMs using Ghidra

Austin Clements will give us an introduction to reverse engineering by taking apart a Sega Genesis ROM using the open source Ghidra tool suite

<iframe width="560" height="315" src="https://www.youtube.com/embed/TziD0EHVlIE" title="Below-C-Level October 2023: Austin Clements - Reversing SEGA ROMs using Ghidra" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-08-01T18:00:00-06:00 - Dan Philips: Filesystems, Everywhere

This week we have Dan Phillips talking about Wasm and filesystems. Here is the abstract:

Title: Filesystems, Everywhere

WebAssembly, described by some as the “Final Abstraction,” allows for a lot of opportunity to improve upon many of the basic building blocks of computing, as we know them today. One of the most prominent of these is filesystems.

The unix philosophy that “everything is a file” is a fundamental idea that powers platforms that currently run a huge amount of software. If we want Wasm to be a deployment target for existing applications, we have to grapple with this fact and figure out how we intend to approach the problem of filesystems and filesystem-like entities in this new platform.

One approach: A WebAssembly-first Filesystem. This talk will discuss the rationale for and development of the `wasm-vfs` and `wasm-libc` projects that allow for the use of a standard filesystem, virtualized, all within a Wasm module. We will also examine how this new paradigm can be enabled by and further expanded with new features planned for the Wasm spec around virtualization, “share-everything” dynamic linking, and resource handles and types.

A WebAssembly-powered computing platform allows us to think outside of the distinctions of Userspace and Kernelspace – so why not see how far that can take us? Starting with filesystems, we’ll see how some of the same concepts of virtualization from the kernel can be applied to new environments where a filesystem can exists close to your users, your application, on the cloud, and on devices, all without worrying about the all-too-familiar costs of syscall execution in traditional Operating Systems.


<iframe width="560" height="315" src="https://www.youtube.com/embed/uj864_mI0gI" title="Below-C-Level August 203: Dan Phillips - Filesystems Everywhere" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## 2023-07-18T18:00:00-06:00 - Neil Mock: Virtio

**Note**: This will be the third Tuesday, not the first, because the organizers will be out of town.

Neil Mock will be talking about virtio. More details to come soon.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/dfMkWQOJzUA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-06-06T18:00:00-06:00 - Robert Ismo: Building Semantic Search

Robert Ismo will talk about semantic search. Exploring methods of finding relevant documents from a simple query and some of the mathematics to make it performant.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/uqVx6gCOrck" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## 2023-05-02T18:00:00-06:00 - Benjamin Eckel: Running JavaScript in Wasm

Benjamin Eckel will talk about how [Extism](https://extism.org/) is able to run [JavaScript
in Wasm](https://github.com/extism/js-pdk). We'll dig into the concepts behind how we leverage [QuickJS](https://bellard.org/quickjs/) and how
we are able to make it fast.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/cIsEbeuloD0" title="Below-C-Level May 2023: Running JavaScript in Wasm" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-04-04T18:00:00-06:00 - Aaron Lee: Google's Maglev Paper

Aaron Lee will present about [Maglev: A Fast and Reliable Software
Network Load Balancer](https://research.google/pubs/pub44824/), which
lays out a way to build a load balancer that serves more traffic than
any single machine could.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/qQdHJvW7vOQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-03-07T18:00:00-06:00 - Benjamin Eckel: First Meeting, and Presenting Smol

Welcome to our first meeting! On the agenda we have:

- Introductions
- Administrative business
- Ben will present [smol: An educational VM in Javascript](https://github.com/bhelx/smol)

If you want to give a talk, or want to build an idea into a talk we'll
also spend some time filling out our schedule.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/D7GxyHxyYA8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

