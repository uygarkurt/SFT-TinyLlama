# Instruct-Tune TinyLlama

<div align="center">
    <a href="">
        <img alt="open-source-image"
		src="https://img.shields.io/badge/%E2%9D%A4%EF%B8%8F_Open_Source-%2350C878?style=for-the-badge"/>
    </a>
    <a href="https://youtu.be/6XeTk8cZUsM">
        <img alt="youtube-tutorial"
        src="https://img.shields.io/badge/YouTube_Tutorial-grey?style=for-the-badge&logo=YouTube&logoColor=%23FF0000"/>
    </a>
</div>
<br/>
<div align="center">
    <p>Liked our work? give us a ⭐!</p>
</div>

<p align="center">
  <img src="./assets/sample.png" height="70%" width="70%"/>
</p>

TThis repository contains an easy-to-use and understand code to instruct-tune, or SFT (supervised fine tuning) [TinyLlama](https://github.com/jzhang38/TinyLlama) to create ChatGPT like chatbots (stateless).

I'll be using TinyLlama, however as stated in their repository it uses the same architecture as [Llama 2](https://arxiv.org/abs/2307.09288). If you want to use Llama 2 it'll be probably fine.

We'll be using both [Alpaca Dataset](https://crfm.stanford.edu/2023/03/13/alpaca.html), and a custom dataset that we'll load from our local machine.

Prompt format we'll be using is
```
Below is an instruction that describes a task, paired with an input that provides further context. Write a response that appropriately completes the request.

### Instruction:
{prompt}

### Input:
{context}

### Response:
```

There are lots of prompting formats. I explained detailly when to use which prompting format detailly in the video.

## YouTube Tutorial
<div align="center">
    <a href="https://youtu.be/6XeTk8cZUsM">IInstruct-Tune TinyLlama to Create ChatGPT Like Chatbots | Custom Dataset, Huggingface, SFT</a>
    <br>
    <br>
    <a href="https://youtu.be/6XeTk8cZUsM">
        <img src="./assets/tn-1.png" height="85%" width="85%%"/>
    </a>
</div>