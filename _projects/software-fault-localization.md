---
name: A Comparison of Software Fault Localization Methods
layout: project
url: software-fault-localization
title: A Comparison of Software Fault Localization Methods
date: 2020-05-24
photo: sfl.jpg
description: A research paper written for CSC 455 at Missouri State University for the Summer 2020 Semester discussion Fault Localization.
---

## Introduction
During the Summer 2020 Semester at Missouri State University, I was tasked with designing an improved Software Fault Localization technique as part of my first researched based class. My team decied to develop a new technique as a combination of Spectrum and Slice based testing, to prove the usefullness of such technique.

## Abstract
Abstract — Software Fault Localization is a growing and important topic within the field of Computer Science. We discuss several popular Software Fault Localization (SFL) techniques, their advantages and disadvantages, and limitations for each one. Slice-based, spectrum-based, and block-based with a novel kernel measure are each discussed before introducing a new contribution to the field. We then introduce a technique composed of slicing and spectrum-based localization, designed to improve the fault localization process. Our technique takes advantage of several commonly used SFL tools and utilities, and makes an attempt to prove the validity of a solution involving GZoltar and a manual slicing of a program to identify and detect the location of software faults with a numerical and visual approach. The objective of the spectrum-based is to identify the location of a fault, where the slice-based component is designed to reduce the surface area that a bug takes up, allowing for much quicker testing and an even better ability to quickly find faults throughout a program of any given size. After conducting our experiment and data collection, we propose the creation of an automated slice-based tool to ensure accurate slicing occurs, then, we propose a combination tool that conducts spectrum-slice based testing automatically for a user. The creation of such tool would drastically help the field of Software Fault Localization. Finally, we discuss and acknowledge possible threats of validity to our idea and justify our rationale and reasoning behind the presented improvement.

<center>
{% include elements/button.html link="/assets/software-fault-localization-dl.pdf" text="Download Paper" %}
</center>