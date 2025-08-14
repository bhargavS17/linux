---
title: "Kernels and Abstraction ..."
seoTitle: "Kernels and Abstraction"
seoDescription: "What are Kernels?
What is low-level programming?
Who is Terry A Davis?"
datePublished: Thu Aug 14 2025 18:30:23 GMT+0000 (Coordinated Universal Time)
cuid: cmebqii0u000402l85ct73e5b
slug: kernels-and-abstraction
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/NVXLumijg5A/upload/bd5361107e6a62b3b331c8c6ab6d9a7b.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1755187170097/058f08b8-f6fe-4b29-9425-caeb5e19e3d1.jpeg
tags: kernel, abstraction, uefi, bootloader

---

If you are an intellect, you are going to get 70% of the things I write in here …

The world is fundamentally an abstraction. From the protons to photons, from [quarks](https://en.wikipedia.org/wiki/Quark) to [qubit](https://en.wikipedia.org/wiki/Qubit), everything is abstract. While solving classical physics problems from IE Irodov, I’m sure you must have encountered the rotation chapter, this was the toughest chapter from my POV.

Treat an OS like an onion, which has layers inside layers. These layers are called [abstraction](https://en.wikipedia.org/wiki/Abstraction).

Let us start from the very basics :

1. [Bare Metal Hardware](https://en.wikipedia.org/wiki/X86)
    
2. [UEFI](https://en.wikipedia.org/wiki/UEFI)
    
3. Bootloaders
    
4. Kernels
    

## 1\. Bare Metal Hardware

### #define [computer\_architecture](https://www.gentoo.org/downloads/) x86

What do we mean by Computer Architecture? Just like the construction of a building has phases that starts with the structural layouts, every modern system has each an architecture of its own. The common ones include ARM, AMD, SPARC and ***x86*** which I am sure might be the architecture of the system you are reading this on. Some modified architectures also include FPGA, STM-32 and RISC-V…

## 2\. [***UEFI***](https://en.wikipedia.org/wiki/Insyde_Software) :: Unified Extensible Firmware Interface

### #define firmware not\_an\_insyde

This is where the initial layer of abstraction occurs, according to my understanding. Firmware itself serves as an abstraction. ***UEFI*** is meticulously crafted by highly specialized engineers proficient in hardware-specific abstraction techniques, such as SystemVerilog. The UEFI is a signed product often carried out by companies like Microsoft, Google & Apple.

## 3.[***Bootloaders***](https://en.wikipedia.org/wiki/Bootloader) :: An Engineer’s Nightmare

### #include &lt;sleeping.h&gt;

What are Bootloaders? If we going by the literal meaning, it makes no sense at all…

In the process of OS development, this is where a specialized engineer may knock on your door and say *“ It works on my machine.” Cliche.*

Tools like Yocto, Buildroot, etc are tailored for this specific purposes provided you know what you are aiming for, at all times.

Most modern architectures including the IoT firmwares, make use of System Verilog to create appealing Bootloaders and BIOS \[Basic Input Output System\].

## 4.[***Kernels***](https://kernel.org/) :: The userspace & the \*systemspace

The kernel is an interface, useful for managing the *processes. memory, networking and virtual files.*

The most recent [linux](https://endeavouros.com/) kernel version is 6.15.9-arch1-1 for my distribution…

**Note ::**  
The [linux](https://en.wikipedia.org/wiki/History_of_Linux) operating system, originally developed by Linus Torvalds, is an Open Source Operating System unlike Windows and MacOS. Although there are some similarities between macos and linux, it is rightful to say that MacOS is a Unix Derivative whereas Linux is POSIX compliant.

In layman language, MacOS and Linux are natively cousins.

Any kind of questions are welcomed, you can reach out to me at careers.shrish@gmail.com