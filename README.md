# Awesome Chart Understanding

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRWelcome](https://img.shields.io/badge/PRs-Welcome-red)](https://img.shields.io/badge/PRs-Welcome-red)

A curated list of recent and past chart understanding work. **The repository will be continuously updated 📝**.


## Table of Contents 
*  [Tasks/ Resources](#tasks)
*  [Methods](#methods)
*  [Evaluation](#evaluation)


## Tasks

### Chart Question Answering 

**Factoid Questions**

- [DVQA: Understanding Data Visualizations via Question Answering](https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf). Kushal Kafle, Brian Price, Scott Cohen, Christopher Kanan. CVPR 2018.
- [FigureQA: An Annotated Figure Dataset for Visual Reasoning](https://arxiv.org/abs/1710.07300). Samira Ebrahimi Kahou, Vincent Michalski, Adam Atkinson, Akos Kadar, Adam Trischler, Yoshua Bengio. ICLR 2018 Workshop.
- [LEAF-QA: Locate, Encode & Attend for Figure Question Answering](https://openaccess.thecvf.com/content_WACV_2020/papers/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.pdf). Ritwick Chaudhry, Sumit Shekhar, Utkarsh Gupta, Pranav Maneriker, Prann Bansal, Ajay Joshi. WACV 2020.
- [STL-CQA: Structure-based Transformers with Localization and Encoding for Chart Question Answering](https://aclanthology.org/2020.emnlp-main.264/). Hrituraj Singh, Sumit Shekhar. EMNLP 2020.
- [PlotQA: Reasoning over Scientific Plots](https://arxiv.org/abs/1909.00997). Nitesh Methani, Pritha Ganguly, Mitesh M. Khapra, Pratyush Kumar. WACV 2020.
- [MapQA: A Dataset for Question Answering on Choropleth Maps](https://arxiv.org/abs/2211.08545). Shuaichen Chang, David Palzer, Jialin Li, Eric Fosler-Lussier, Ningchuan Xiao. Arxiv 2022.
- [ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning](https://aclanthology.org/2022.findings-acl.177/). Ahmed Masry, Xuan Long Do, Jia Qing Tan, Shafiq Joty, Enamul Hoque. ACL 2022 Findings.
- [MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models](https://arxiv.org/abs/2310.02255). Pan Lu, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, Jianfeng Gao. Arxiv 2023.
- [ChartBench: A Benchmark for Complex Visual Reasoning in Charts](https://arxiv.org/abs/2312.15915). Zhengzhuo Xu, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, Jian Guo. Arxiv 2023



**Long-form Questions**  

- [OpenCQA: Open-ended Question Answering with Charts](https://aclanthology.org/2022.emnlp-main.811/). Shankar Kantharaj, Xuan Long Do, Rixie Tiffany Leong, Jia Qing Tan, Enamul Hoque, Shafiq Joty. EMNLP 2022.

### Chart Captioning (Summarization)

- [Figure Captioning with Relation Maps for Reasoning](https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf). Charles Chen, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, Ryan Rossi. WACV 2020.
- [Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model](https://aclanthology.org/2020.inlg-1.20/). Jason Obeid, Enamul Hoque. INLG 2020
- [SciCap: Generating Captions for Scientific Figures](https://aclanthology.org/2021.findings-emnlp.277/). Ting-Yao Hsu, C Lee Giles, Ting-Hao Huang. EMNLP 2021
- [Chart-to-Text: A Large-Scale Benchmark for Chart Summarization](https://aclanthology.org/2022.acl-long.277/). Shankar Kantharaj, Rixie Tiffany Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, Shafiq Joty. ACL 2022.
- [LineCap: Line Charts for Data Visualization Captioning Models](https://ieeexplore.ieee.org/abstract/document/9973197). Anita Mahinpei, Zona Kostic, Chris Tanner. 2022 IEEE VIS.
- [VisText: A Benchmark for Semantically Rich Chart Captioning](https://aclanthology.org/2023.acl-long.401/). Benny Tang, Angie Boggust, Arvind Satyanarayan. ACL 2023.

### Chart Caption Factual Error Correction

- [Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning](https://arxiv.org/abs/2312.10160). Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji. Arxiv 2023.


### Chart Fact-checking

- [ChartCheck: An Evidence-Based Fact-Checking Dataset over Real-World Chart Images](https://arxiv.org/abs/2311.07453). Mubashara Akhtar, Nikesh Subedi, Vivek Gupta, Sahar Tahmasebi, Oana Cocarascu, Elena Simperl. Arxiv 2023.
- [Reading and Reasoning over Chart Images for Evidence-based Automated Fact-Checking](https://arxiv.org/abs/2301.11843). Mubasharar Akhtar, Oana Cocarascu, Elena Simperl. EACL 2023 Findings.
  
## Methods

### Pre-trained Vision-language Models

- [Enhanced Chart Understanding via Visual Language Pre-training on Plot Table Pairs](https://aclanthology.org/2023.findings-acl.85/). Mingyang Zhou, Yi Fung, Long Chen, Christopher Thomas, Heng Ji, Shih-Fu Chang. ACL 2023 Findings.
- [MatCha: Enhancing Visual Language Pretraining with Math Reasoning and Chart Derendering](https://aclanthology.org/2023.acl-long.714/). Fangyu Liu, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Yasemin Altun, Nigel Collier, Julian Eisenschlos. ACL 2023.
- [UniChart: A Universal Vision-language Pretrained Model for Chart Comprehension and Reasoning](https://aclanthology.org/2023.emnlp-main.906/). Ahmed Masry, Parsa Kavehzadeh, Xuan Long Do, Enamul Hoque, Shafiq Joty. EMNLP 2023.
- [Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding](https://proceedings.mlr.press/v202/lee23g/lee23g.pdf). Kenton Lee, Mandar Joshi, Iulia Raluca Turc, Hexiang Hu, Fangyu Liu, Julian Martin Eisenschlos, Urvashi Khandelwal, Peter Shaw, Ming-Wei Chang, Kristina Toutanova. ICML 2023.

### Tool Augmentation
- [DePlot: One-shot visual language reasoning by plot-to-table translation](https://aclanthology.org/2023.findings-acl.660/). Fangyu Liu, Julian Eisenschlos, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Wenhu Chen, Nigel Collier, Yasemin Altun. ACL 2023 Findings.
- [Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning](https://arxiv.org/abs/2312.10160). Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji. Arxiv 2023.
- [Do LLMs Work on Charts? Designing Few-Shot Prompts for Chart Question Answering and Summarization](https://arxiv.org/abs/2312.10610). Xuan Long Do, Mohammad Hassanpour, Ahmed Masry, Parsa Kavehzadeh, Enamul Hoque, Shafiq Joty. Arxiv 2023.
- [DOMINO: A Dual-System for Multi-step Visual Language Reasoning](https://arxiv.org/abs/2310.02804). Peifeng Wang, Olga Golovneva, Armen Aghajanyan, Xiang Ren, Muhao Chen, Asli Celikyilmaz, Maryam Fazel-Zarandi. Arxiv 2023. 
- [StructChart: Perception, Structuring, Reasoning for Visual Chart Understanding](https://arxiv.org/abs/2309.11268). Renqiu Xia, Bo Zhang, Haoyang Peng, Hancheng Ye, Xiangchao Yan, Peng Ye, Botian Shi, Yu Qiao, Junchi Yan. Arxiv 2023.


### Large Vision-language Models 

**Tailored for Chart Understanding** 
- [ChartLlama: A Multimodal LLM for Chart Understanding and Generation](https://arxiv.org/abs/2311.16483). Yucheng Han, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang. Arxiv 2023.
- [MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning](https://arxiv.org/abs/2311.10774). Fuxiao Liu, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, Dong Yu. Arxiv 2023.
- [ChartAssisstant: A Universal Chart Multimodal Language Model via Chart-to-Table Pre-training and Multitask Instruction Tuning](https://arxiv.org/abs/2401.02384). Fanqing Meng, Wenqi Shao, Quanfeng Lu, Peng Gao, Kaipeng Zhang, Yu Qiao, Ping Luo. Arxiv 2024.
- [ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning](https://arxiv.org/abs/2402.12185). Renqiu Xia, Bo Zhang, Hancheng Ye, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Min Dou, Botian Shi, Junchi Yan, Yu Qiao. Arxiv 2024.
- [ChartInstruct: Instruction Tuning for Chart Comprehension and Reasoning](https://arxiv.org/abs/2403.09028). Ahmed Masry, Mehrad Shahmohammadi, Md Rizwan Parvez, Enamul Hoque, Shafiq Joty. Arxiv 2024.
- [FigurA11y: AI Assistance for Writing Scientific Alt Text](https://www.llwang.net/assets/pdf/2024_singh_figura11y_iui.pdf). Nikhil Singh, Andrew Head, Lucy Lu Wang, Jonathan Bragg. Arxiv 2024.

**General**

- [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485). Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee. NeurIPS 2023.
- [Gemini: A Family of Highly Capable Multimodal Models](https://arxiv.org/abs/2312.11805). Gemini Team Google. Arxiv 2023.
- [GPT-4V](https://openai.com/research/gpt-4v-system-card). OpenAI. 2023.


## Evaluation

### Faithfulness/ Factuality

- [Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning](https://arxiv.org/abs/2312.10160). Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji. Arxiv 2023.

