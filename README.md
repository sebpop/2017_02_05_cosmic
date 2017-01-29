# 2017_02_05_cosmic
Slides for COSMIC'17 workshop.

$ apt-get install latex-beamer
$ pdflatex

Title: "Optimizing the software stack of a cosmic proportions cluster of
multi-core machines"

Abstract: With more than a billion devices, Android is the largest heterogeneous
multi-node multi-core machine built in  a sustainable, very informal, and ad-hoc
way in the past few years.  Its  size in number of cores and computational power
surpasses by  far all the  super-computers tracked on top500.org.   The software
running  on this  heterogeneous machine  of  cosmic proportions  is composed  of
open-source libraries mostly written in C  and C++.  It originates from a common
source base,  the Android  Open Source  Project (AOSP)  that may  be customized,
updated, and deprecated with time.

I will present the open source tools that we use in the compiler group at SARC
(Samsung Austin R&D Center) to analyze the performance of AOSP, how to detect
opportunities to improve performance, our current contributions to AOSP, and I
will finish by showing how to prioritize the performance work and how to measure
the overall impact of a code optimization in terms of energy consumption and
improvements to the end-user experience.

Bio: Sebastian Pop is a compiler engineer and team leader at Samsung Austin R&D
Center where he works on GCC, LLVM, and the AOSP libraries to improve the
performance of the Samsung Exynos line of processors through contributions to
the open source projects.  In the past he worked on LLVM at Qualcomm Innovation
Center in Austin, TX and on GCC at Advanced Micro Devices in Austin, TX.  He
graduated with a PhD in computer science from Ecole des mines de Paris.

