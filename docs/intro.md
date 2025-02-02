---
sidebar_position: 1
---
# Welcome

Welcome to this course on Prompt Engineering! 

I like to think of Prompt Engineering (PE) as "**How communicate with AI to get it to do what you want**". 

With many of the recent advances in AI,
this has become a particularly important skill.
This course focuses on applied prompt engineering techniques. Minimal knowledge of 
machine learning is expected; if you have no idea what any of this stuff means, read [this](#novices).

## The single most important part of this course is your feedback!
If you have any questions, comments, or suggestions, please make an **[issue](https://github.com/trigaten/Learn_Prompting/issues/new/choose)**, email me at learnprompting@gmail.com, or reach out over [Discord](https://learnprompting.org/discord)/[Twitter](https://twitter.com/learn_prompting).

Even the smallest amount of feedback is very helpful!

## Course Philosophy

**Quick Iterations** - Since new PE content is published almost daily, 
I will update this course frequently with short articles about new techniques.
Let me know what you want to hear more about!

Part of this philosophy is **error iteration**; if you ever see something that you
don't quite understand, even something small, that's on me. **Please make an [issue](https://github.com/trigaten/Learn_Prompting/issues/new/choose)**!

**Focus on Practicality** - I will focus on applied, practical techniques that you can use
immediately for your applications.

**Examples ASAP** - I try to put examples in the articles as soon as possible,
so that you can get a feel for the techniques as soon as possible.

I'll philosophize more about this when I have time to 😊

## How to read

It is not necessary to read all chapters in order. Read what interests you!

That being said, Basics is a good place to start,
and it discusses some very simple, but powerful, prompt engineering techniques.

## Chapters

Here is a quick summary of each chapter:

**Basics**: Intro to PE and simple PE techniques

**Advanced Applications**: Some very powerful, but more advanced applications of PE

**Applied Prompting**: Some complete walkthroughs of the PE process written by community members

**Reliability**: How to make LLMs more reliable

**Images**: PE for text to image models like DALLE and Stable Diffusion!

**Prompt Injection**: Hacking, but for PE

**Prompting IDEs**: Different PE tools

**Prompt Tuning**: Fine tune prompts with gradients

## Novices

If you already have a general idea of prompt engineering, you can skip this section.

Otherwise, here is a quick introduction to AI and prompt engineering. Before we get into that,
it is important to note that you don't need any technical background to do prompt engineering.
Most of it is trial and error, and you can learn as you go.

In recent years, researchers have developed a new class of AI models called **Language Models** (LMs).
These models are trained on large amounts of text, and can be used to generate text. Humans can also interact
with these models by typing in a some text (a prompt) and seeing what the model says in response. 
[This website](https://beta.openai.com/playground) is a good place 
to experiment with talking to a language model. Here is a screengrab from the website:

import diverse from './assets/novice.png';

<div style={{textAlign: 'center'}}>
  <img src={diverse} style={{width: "750px"}} />
</div>

I just typed in "What is the opposite of the word start?" and the AI said "Stop". 
Pretty cool! Try asking it to write a story, solve a math problem, or philosophize about the meaning of life.

Sometimes when you ask questions in a better way, the AI will give you a better answer. 
The process of figuring out these good ways of asking questions is called **prompt engineering**.
That is the focus of the rest of this guide. 
