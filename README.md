# Transformer From Scratch: Burmese to English Translation

This notebook is a barebones implementation of a Transformer model for Burmese-to-English translation. 

This is NOT optimized for performance.  
It was built purely to understand the internals of the Transformer architecture, things like multi-head attention, positional encoding, masking, and more.

## Why I Built This

I've always learned best by getting my hands dirty. I wanted to go beyond just using prebuilt models and really understand the math and flow of information in a transformer. The model doesn't perform well (in fact, it's really bad), but that's not what I was aiming for.

Instead, the focus was on:
- Understanding the architecture from the ground up
- Implementing each block step by step
- Making sense of tensor shapes and operations
- Getting comfortable with the internals rather than relying on libraries

The entire code is influenced by Umar Jaamil’s incredible explanation on YouTube, this notebook is basically my interpretation of his walkthrough, written in my own way to solidify my understanding.

## What's Inside

- Custom tokenizer (character-level for Burmese, word-level for English)
- Input and positional embeddings
- Encoder and decoder with multi-head attention blocks
- Masking and attention logic from scratch
- Greedy decoding for inference

## A Request

I'm still learning and open to feedback. If you spot mistakes, inefficiencies, or just have better ways to do things, please feel free to drop your thoughts. I'd really love to improve and understand this deeper.

Thanks for checking it out!

– Jithu