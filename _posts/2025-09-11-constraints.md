---
layout: post
title: "Helpful Constraints"
---

Programming imposes constraints on langauge use that make it more suitable for generative AI than many everyday uses of language. 

The grammatical rules for normal language use are flexible, complex and unsufficiently defined. The LLM has supposedly already been trained to generate text that conforms to the language grammer, and it is unlikely that any evaluation of the output to identify grammer issues would prove effective. However, programming languages have strict, explicitly defined; which means that linters and compilers can verify that generated output is syntactially valid. 

Normal language use *does* things, but the work done by everyday language is done out in the world. In contrast, programs do work in the computer. When an LLM generates a program, not only can we verify that it is syntically valid, but we can use tests and contracts to verify that the program maps inputs to outputs as expected.

A program can also be constrained by its runtime environment. We can ensure that a given program cannot access parts of the system without looking at the program's code. By running in containers, or virtual machines, or kernel imposed priveleges. 

I can ask an LLM to generate a legal contract. But without being a lawyer, I cannot verify that it conforms to the syntactical rules of legal contracts. Even as a lawyer, I could not prove that the contract does what I wanted to accomplish. And I cannot effectively guard against undesireable side-effects from executing the contract. 
