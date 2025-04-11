---
layout: single
title: "Publications"
permalink: /Publications/
author_profile: true
---

<style>
.publication-item {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 30px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.publication-item h2 {
    margin-top: 0;
    color: #2e4057;
    border-bottom: 2px solid #2e4057;
    padding-bottom: 10px;
}

.publication-item .authors {
    color: #666;
    font-style: italic;
    margin: 10px 0;
}

.publication-item .submission {
    color: #888;
    font-size: 0.9em;
    margin-bottom: 15px;
}

.publication-item .abstract {
    background-color: #f8f9fa;
    border-left: 4px solid #2e4057;
    padding: 15px;
    margin: 15px 0;
    font-size: 0.95em;
    line-height: 1.6;
}

.publication-item .workflow {
    margin: 20px 0;
    text-align: center;
}

.publication-item .workflow img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
</style>

## 2024

### BioResearcher: 自动化生物医学研究系统
<div class="publication-item">
<h2><a href="https://arxiv.org/abs/2412.09429">From intention to implementation: Automating biomedical research via llms</a></h2>
<div class="authors"><b>Yi Luo</b>, Linghang Shi, Yihao Li, Aobo Zhuang, Yeyun Gong, Ling Liu, Chen Lin</div>
<div class="submission">Submission to SCIENCE CHINA Information Sciences</div>

<div class="abstract">
We develop BioResearcher, an end-to-end automated biomedical research system. The system adopts a modular design and hierarchical learning approach to automate the entire research workflow. Given a research objective, BioResearcher autonomously executes a series of research processes, including literature and dataset retrieval, extraction and analysis of relevant experimental reports, as well as experimental design and programming implementation.
</div>

<!-- <div class="workflow">
    <img src="/images/placeholder1.jpg" alt="Workflow Image" style="max-width: 100%; height: auto;">
</div> -->
</div>

### DQABench: 数据库问答基准与评估
<div class="publication-item">
<h2><a href="https://arxiv.org/abs/2409.04475">Revolutionizing Database Q&A with Large Language Models</a></h2>
<div class="authors">Yihang Zheng, Bo Li, Zhenghao Lin, <b>Yi Luo</b>, Xuanhe Zhou, Chen Lin, Jinsong Su, Guoliang Li, Shifu Li</div>
<div class="submission">Submission to KDD 2025 Datasets and Benchmarks Track</div>

<div class="abstract">
We design a comprehensive evaluation benchmark for database QA and a LLM-based database QA system. The benchmark includes a dataset, a GPT-4-based benchmark construction method, and an evaluation framework. The complete QA system consists of: a) a carefully pre-trained and fine-tuned LLM, b) a question classification routing module, c) a prompt template engineering (PTE) module, d) a retrieval-augmented generation (RAG) module, and e) a tool invocation module. The benchmark thoroughly quantifies the database QA capabilities of nine different LLMs in both Chinese and English. The full QA system enhances the overall performance of a 13B-parameter LLM by 44\% in database QA tasks, achieving close or even superior performance to advanced models like GPT-4 in certain domains.
</div>

<!-- <div class="workflow">
    <img src="/images/placeholder2.jpg" alt="Workflow Image" style="max-width: 100%; height: auto;">
</div> -->
</div>

### Guide-Align: 基于指南库的安全输出
<div class="publication-item">
<h2><a href="https://arxiv.org/abs/2403.11838">Ensuring Safe and High-Quality Outputs: A Guideline Library Approach</a></h2>
<div class="authors"><b>Yi Luo</b>, Zhenghao Lin, Yuhao Zhang, Jiashuo Sun, Chen Lin, Chengjin Xu, Xiangdong Su, Yelong Shen, Jian Guo, Yeyun Gong</div>
<div class="submission">NAACL 2024</div>

<div class="abstract">
We propose Guide-Align, an innovative approach to 
address the significant risks of bias, privacy 
leakage, and harmful content generation in LLMs. 
Existing rule-based alignment techniques often 
suffer from three key limitations: imprecise rule 
definitions, insufficient coverage, and limited 
risk perception capabilities. Guide-Align overcomes 
these challenges through three key steps: 1) A 
safety-trained language model analyzes input data 
for potential risks and generates corresponding 
safety guidelines, building a comprehensive 
guideline library; 2) A retrieval model is trained 
to match input content with corresponding 
guidelines; 3) During inference, the retrieval 
model extracts applicable rules from the library to 
steer LLM outputs toward safe, high-quality 
responses. Furthermore, we leverage open datasets 
to generate alignment data for fine-tuning, 
yielding our final model, Labrador.
</div>

<!-- <div class="workflow">
    <img src="/images/placeholder3.jpg" alt="Workflow Image" style="max-width: 100%; height: auto;">
</div> -->
</div>

### Iter-CoT: 迭代引导的思维链增强
<div class="publication-item">
<h2><a href="https://arxiv.org/abs/2304.11657">Enhancing Chain-of-Thoughts Prompting with Iterative Bootstrapping</a></h2>
<div class="authors">Jiashuo Sun*, <b>Yi Luo</b>*, Yeyun Gong, Chen Lin, Yelong Shen, Jian Guo, Nan Duan</div>
<div class="submission">NAACL 2024 Findings</div>

<div class="abstract">
We propose Iter-CoT, a novel iterative self-correction framework. This method enables the model to refine its reasoning chains autonomously, thereby producing more accurate and comprehensive reasoning chains. Additionally, Iter-CoT selectively incorporates challenging yet solvable questions as exemplars, enhancing the model's generalization capability across problems of varying difficulty levels.
</div>

<!-- <div class="workflow">
    <img src="/images/placeholder4.jpg" alt="Workflow Image" style="max-width: 100%; height: auto;">
</div> -->

</div>
