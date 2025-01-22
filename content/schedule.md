---
title: "Schedule"
date: 2023-02-10T11:19:01-06:00
draft: false
---

# Upcoming

## 2025-02-04T18:00:00-06:00 - <ins>[Flora Petterson](https://codebeamnyc.com/participants/flora-petterson/)</ins> - Building a Highly Available, Distributed Streaming System Using Only Elixir and The BEAM

The [Publish-Subscribe Messaging Pattern](https://en.wikipedia.org/wiki/Publish%E2%80%93subscribe_pattern) is an extremely valuable architectural tool in building scalable applications. However, the standard practice of relying on external brokers to manage queuing for incoming messages adds an unnecessary dependency into your system. Instead, you can utilize the benefits of a continuously available system powered by the [Erlang VM](https://www.erlang.org/blog/a-brief-beam-primer/) to safely and reliably store messages from a publication within your application until they are sent to a subscriber. In this talk, I will share lessons learned from working on [HCA’s Waterpark](https://elixirmerge.com/p/improving-healthcare-outcomes-with-elixirs-actor-model), a data integration engine that uses [Elixir](https://elixir-lang.org/) and the [BEAM](https://www.erlang-solutions.com/blog/the-beam-erlangs-virtual-machine/) to be a continuously available streaming system using a [distributed database](https://en.wikipedia.org/wiki/Distributed_database) that never touches disk.

# Archive

## 2025-01-07T18:00:00-06:00 - <ins>[Adam Chalmers](https://adamchalmers.com/)</ins> - Vote on a Talk

[Adam Chalmers](https://adamchalmers.com/) will present one of the following two talks. We'll vote on which one to hear at pizza time.
- Building your own programming language
- ~~Keeping API servers, clients, and schemas in sync by generating them programmatically from their definition or code~~

<!-- CANCELED
## 2025-01-07T18:00:00-06:00 - Jeff Read - An Implementation of the Deflate Algorithm

Jeff Read will be discussing the [Deflate](https://en.wikipedia.org/wiki/Deflate) algorithm, a general data compression algorithm first developed by Phil Katz for his [PKZIP](https://www.pkware.com/products/pkzip) software, and now widely used in the PNG image format, gzip compressed files, and other applications. Mr. Read will present an implementation of the algorithm he wrote in [Scheme](https://www.scheme.org/) and talk about the details of the implementation and the challenges he faced writing it.
-->

## 2024-08-06T18:00:00-05:00 - Aaron Lee - Mob Programming a Web Server From Scratch

We are going to try something different. We can try mob programming a web server from scratch. We'll open an editor on the projector and as a group walk through some basics of HTTP. This will be a great opportunity to learn from each other. This is our first try at mob programming, if it works well there are lots of services we can try and tackle in later meetings.

Please note the change in location, we will be at SCALE, the same location as Front End Party. They have free coworking on Tuesdays if you bring fruit share. Some of us will be at SCALE before the meetup.

## 2024-03-05T18:00:00-06:00 - Vanessa Pyne - lo-fi spy: video, steganography, and you

One time I internet searched the term “steganography”, thinking it was the study of where dinosaurs lived, but discovered it is actually the practice of hiding secret information inside a non-secret message. There are three qualities of a good steganography approach: imperceptibility, robustness, and embedding capacity. I thought to myself, that sounds like dope spy stuff and I definitely want to do that. It turns out video can be a fantastic non-secret message format in which to conceal covert messages. There are a few common approaches to make data undetectable, including bit manipulation ie the Least Significant Bit algorithm, as well as exploitation of error codes and of course, AI. Oh and there is this cool cryptographic concept of secret sharing, which can be used in video steganography to ensure the message is retrievable, even if some of the secret bits are missing. And embedding capacity is almost a given, as video files are often large and compressed. This talk (originally given at Demuxed in October) will go more in depth into how these methods work but don’t worry, the scary LSB and secret sharing maths will be softened with jokes and gifs.

## 2024-02-06T18:00:00-06:00 - Lightning Talks

We had some lightning talks

## 2023-12-05T18:00:00-06:00 - Dominique Saulet - WebAssembly Unpacked: A Guide to Wasm

Perhaps you’ve heard of WebAssembly (Wasm) and all of the associated refrains: virtual Instruction Set Architecture (ISA), web standard, stack-based virtual machine, fantasy computer, and compilation target. Perhaps you’ve been told of its feature set: sandboxed security, highly performant and portable byte code format, and perhaps even, you’ve heard the prophecies: the holy grail of 'write once, run anywhere' (sorry Java), the common denominator for all compute, a bridge from languages, high and low, to platforms in the cloud and off to the far edge. But the truth, you see, is that Wasm is here. It’s all around you. Even now, in your browser, in your streaming services, in your serverless functions, extending your SaaS platforms, and running your AI models. And so, together, let’s unpack this alien tech and all of the arcane words that describe it, bit by bit, byte by byte, to discover what strange mechanisms make it tick, and what it means for the future.

<iframe width="560" height="315" src="https://www.youtube.com/embed/7Fe_bSvOU6c?si=0sv29DnCRr615HOP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-11-07T18:00:00-06:00 - Lightning Talks

- Devin Villegas (Software Eng. @ Netflix) will discuss formal methods
- Benjamin Eckel will talk about a new Wasm runtime he's working on

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
