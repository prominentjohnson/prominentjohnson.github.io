---
layout: bilingual_post
title: "What Is a Diffusion Model?"
date: 2026-04-26 11:00:00 +0200
categories: [ai-concepts]
tags: [diffusion-model, generative-ai, denoising]
description: "A bilingual template post explaining the intuition behind diffusion models."
---

<section data-lang="en" markdown="1">

## One-Sentence Summary

A diffusion model is a generative model that learns how to create data by reversing a gradual noising process.

## Why It Matters

Diffusion models are widely used for image, audio, video, and 3D generation because they can produce high-quality samples while giving the model a stable learning objective.

## Core Ideas

- **Forward process:** gradually add noise to clean data.
- **Reverse process:** train a model to remove noise step by step.
- **Conditioning:** guide generation with text, images, labels, or other signals.
- **Sampling:** start from noise and repeatedly denoise until a sample appears.

## Placeholder Example

For image generation, the model starts with random noise and gradually turns it into a coherent image according to the prompt or condition.

## Notes to Expand Later

- Add a simple noise-to-image diagram.
- Explain the difference between DDPM and latent diffusion.
- Add a short section on why denoising is easier than direct generation.

</section>

<section data-lang="zh" markdown="1">

## 一句话总结

Diffusion model 是一种生成模型，它通过学习“如何反向去噪”来生成数据。

## 为什么重要

Diffusion model 常用于图像、音频、视频和 3D 生成，因为它可以生成高质量样本，同时训练目标相对稳定。

## 核心概念

- **Forward process:** 从干净数据开始，逐步加入噪声。
- **Reverse process:** 训练模型一步一步去除噪声。
- **Conditioning:** 用文本、图像、标签或其他信息引导生成过程。
- **Sampling:** 从随机噪声开始，反复去噪，直到得到最终样本。

## 占位例子

在图像生成中，模型一开始面对的是随机噪声，然后根据 prompt 或其他条件逐步把噪声变成一张有结构的图像。

## 之后可以扩展

- 加一个从噪声到图像的简单示意图。
- 解释 DDPM 和 latent diffusion 的区别。
- 写一小节说明为什么“去噪”比直接生成更容易建模。

</section>
