---
layout: bilingual_post
title: "What Is a Transformer?"
date: 2026-04-26 10:00:00 +0200
categories: [ai-concepts]
tags: [transformer, attention, deep-learning]
description: "A bilingual template post explaining the basic idea behind Transformers."
---

<section data-lang="en" markdown="1">

## One-Sentence Summary

A Transformer is a neural network architecture that uses attention to decide which parts of the input are most relevant to each other.

## Why It Matters

Before Transformers, many sequence models processed text step by step. Transformers made it easier to compare all tokens in a sequence at once, which helped models learn long-range relationships more effectively.

## Core Ideas

- **Tokenization:** split text or other data into small units.
- **Embedding:** turn each token into a vector.
- **Self-attention:** let each token look at other tokens and decide what matters.
- **Feed-forward layers:** transform the attended information into richer features.

## Placeholder Example

In the sentence "the robot picked up the cup because it was light," attention helps the model connect "it" with the likely object being discussed.

## Notes to Expand Later

- Add diagrams for query, key, and value.
- Explain positional encoding.
- Compare encoder-only, decoder-only, and encoder-decoder Transformers.

</section>

<section data-lang="zh" markdown="1">

## 一句话总结

Transformer 是一种神经网络结构，它通过 attention 机制判断输入中哪些部分彼此最相关。

## 为什么重要

在 Transformer 出现之前，很多序列模型会按顺序一步一步处理文本。Transformer 可以让序列中的所有 token 同时互相比较，因此更容易学习长距离依赖关系。

## 核心概念

- **Tokenization:** 把文本或其他数据拆成小单位。
- **Embedding:** 把每个 token 转换成向量。
- **Self-attention:** 让每个 token 观察其他 token，并判断哪些信息重要。
- **Feed-forward layers:** 对 attention 后的信息做进一步变换。

## 占位例子

在句子 “the robot picked up the cup because it was light” 中，attention 可以帮助模型判断 “it” 更可能指代哪个对象。

## 之后可以扩展

- 加 query、key、value 的示意图。
- 解释 positional encoding。
- 比较 encoder-only、decoder-only 和 encoder-decoder Transformer。

</section>
