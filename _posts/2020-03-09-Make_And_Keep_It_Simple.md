---
title: "Make and Keep It Simple"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - CollectiveRTL
  - Open Source Hardware Cores
---

A primary focus of Collective RTL is to make it simple for anyone to participate in the creation
of useful open source hardware cores.  This is a monumental task which I'll attack from different
angles.  The first will be to create a standard form of the required infrustructure.  This will
enable contributors to focus their skills on the core and not on questions like what directory
names to use, or what signal names will make sense to others.

This standard/specification is key to making a library of reusable blocks.  These blocks can
assemble cores and the blocks and cores can be used to build an entire system on chip (SoC).

First is an effort to determine other standards in this area.  Feel free to send me others if I
miss something you feel to be an excellent example.

- [OpenTitan Comportability Definition and Style Guides](https://docs.opentitan.org/doc/rm/)
- [Freescale Semiconductor, Semiconductor Reuse Standard](https://people.ece.cornell.edu/land/courses/ece5760/Verilog/FreescaleVerilog.pdf)
- [NetFPGA Verilog Coding Guidelines](https://github.com/NetFPGA/netfpga/wiki/VerilogCodingGuidelines)
- [FPGACPU.CA Verilog Coding Standard](http://fpgacpu.ca/fpga/verilog.html)
- [RTL Coding Guidelines - Reuse Methodology Manual, for SoC designs](http://twins.ee.nctu.edu.tw/courses/ip_core_01/lab_hw_pdf/RTL_coding_guidelines.pdf)
- [STARC DSG Verilog Rules](https://filebox.ece.vt.edu/~athanas/4514/ledadoc/html/pol_stylgd_verilog_eng.html)
- [STARC DSG VHDL Rules](https://filebox.ece.vt.edu/~athanas/4514/ledadoc/html/pol_stylgd_vhdl_eng.html)

I'm sure there are more of these because now that I've seen a few it seems there could be as many
as there are people.

Interested in helping?  Do you or your company have a solid core reuse standard?  The first step
of the RTL Collecitve is to devise a standard that allows for quick adoption of compliant cores,
so any assistance in creating that standard would be great to have!  In my next post I'll talk
a little about the development of a hardware source standard for the library.
[github-public@collectivertl.org](mailto:github-public@collectivertl.org)

[Join the collective!](mailto:github-public@collectivertl.org?subject=Request to Join Collective RTL)
