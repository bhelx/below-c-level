---
title: "Schedule"
date: 2023-02-10T11:19:01-06:00
draft: false
---

# Upcoming

## 2023-09-05T18:00:00-06:00 - Canceled

Due to scheduling conflicts we will skip September's meeting.

## 2023-10-03T18:00:00-06:00 - TBA

October will be great!

# Archive

## 2023-08-01T18:00:00-06:00 - Filesystems, Everywhere

This week we have Dan Phillips talking about Wasm and filesystems. Here is the abstract:

Title: Filesystems, Everywhere

WebAssembly, described by some as the “Final Abstraction,” allows for a lot of opportunity to improve upon many of the basic building blocks of computing, as we know them today. One of the most prominent of these is filesystems.

The unix philosophy that “everything is a file” is a fundamental idea that powers platforms that currently run a huge amount of software. If we want Wasm to be a deployment target for existing applications, we have to grapple with this fact and figure out how we intend to approach the problem of filesystems and filesystem-like entities in this new platform.

One approach: A WebAssembly-first Filesystem. This talk will discuss the rationale for and development of the `wasm-vfs` and `wasm-libc` projects that allow for the use of a standard filesystem, virtualized, all within a Wasm module. We will also examine how this new paradigm can be enabled by and further expanded with new features planned for the Wasm spec around virtualization, “share-everything” dynamic linking, and resource handles and types.

A WebAssembly-powered computing platform allows us to think outside of the distinctions of Userspace and Kernelspace – so why not see how far that can take us? Starting with filesystems, we’ll see how some of the same concepts of virtualization from the kernel can be applied to new environments where a filesystem can exists close to your users, your application, on the cloud, and on devices, all without worrying about the all-too-familiar costs of syscall execution in traditional Operating Systems.


## 2023-07-18T18:00:00-06:00 - Virtio

**Note**: This will be the third Tuesday, not the first, because the organizers will be out of town.

Neil Mock will be talking about virtio. More details to come soon.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/dfMkWQOJzUA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-06-06T18:00:00-06:00 - Building Semantic Search

Robert Ismo will talk about semantic search. Exploring methods of finding relevant documents from a simple query and some of the mathematics to make it performant.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/uqVx6gCOrck" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## 2023-05-02T18:00:00-06:00 - Running JavaScript in Wasm

Benjamin Eckel will talk about how [Extism](https://extism.org/) is able to run [JavaScript
in Wasm](https://github.com/extism/js-pdk). We'll dig into the concepts behind how we leverage [QuickJS](https://bellard.org/quickjs/) and how
we are able to make it fast.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/cIsEbeuloD0" title="Below-C-Level May 2023: Running JavaScript in Wasm" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-04-04T18:00:00-06:00 - Google's Maglev Paper

Aaron Lee will present about [Maglev: A Fast and Reliable Software
Network Load Balancer](https://research.google/pubs/pub44824/), which
lays out a way to build a load balancer that serves more traffic than
any single machine could.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/qQdHJvW7vOQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## 2023-03-07T18:00:00-06:00 - First Meeting

Welcome to our first meeting! On the agenda we have:

- Introductions
- Administrative business
- Ben will present [smol: An educational VM in Javascript](https://github.com/bhelx/smol)

If you want to give a talk, or want to build an idea into a talk we'll
also spend some time filling out our schedule.

### Recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/D7GxyHxyYA8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

