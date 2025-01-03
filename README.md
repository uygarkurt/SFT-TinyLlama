# Instruct-Tune TinyLlama

<div align="center">
    <a href="">
        <img alt="open-source-image"
		src="https://img.shields.io/badge/Open%20Source%20❤%EF%B8%8F-%2325A162.svg?style=flat"
        style="height: 30px"/>
    </a>
    <a href="https://youtu.be/6XeTk8cZUsM">
        <img alt="youtube-tutorial"
        src="https://img.shields.io/badge/YouTube Tutorial-%23FF0000.svg?logo=youtube&logoColor=white&style=flat"
        style="height: 30px"/>
    </a>
</div>
<div align="center">
    <a href="https://ko-fi.com/uygarkurt" target="_blank">
        <img src="https://storage.ko-fi.com/cdn/brandasset/v2/support_me_on_kofi_blue.png?_gl=1*gypxqi*_gcl_aw*R0NMLjE3MzU5Mzk3MjAuQ2owS0NRaUFzdDY3QmhDRUFSSXNBS0tkV09raHpzemtTUGxadnNOamVpN0FBRDhOdVloTVhuRHJrampCRGhac3FyT2pCY29iRWV0TmNKY2FBbWxiRUFMd193Y0I.*_gcl_au*MjUwODAwNDk1LjE3MzU5NDExMjA.*_ga*MTM3MTUxODgyMS4xNzM1OTQwODYy*_ga_M13FZ7VQ2C*MTczNTk0NTM3MC4yLjEuMTczNTk0NTk4OS40MS4wLjA." alt="Buy Me A Coffee" 
        style="height: 38px"/>
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