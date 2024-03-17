# Awesome Chart Understanding

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRWelcome](https://img.shields.io/badge/PRs-Welcome-red)](https://img.shields.io/badge/PRs-Welcome-red)

A curated list of recent and past chart understanding work based on our survey paper: From Pixels to Insights: A Survey on Automatic Chart Understanding in the Era of Large Foundation Models.

**The repository will be continuously updated 📝. Don't forget to hit the ⭐️ and stay tuned!**

**If you find this resource beneficial for your research, please do not hesitate to cite the paper referenced in the [Citation](#citation) section. Thank you!**


## Table of Contents
*  [Tasks/ Resources](#tasks)
*  [Methods](#methods)
*  [Evaluation](#evaluation)
*  [Citation](#citation)

## Tasks

### Chart Question Answering

**Factoid Questions**

- __DVQA: Understanding Data Visualizations via Question Answering.__ 

  _Kushal Kafle, Brian Price, Scott Cohen, Christopher Kanan._ <img src='https://img.shields.io/badge/CVPR-2018-yellow'> <a href='https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>
- __FigureQA: An Annotated Figure Dataset for Visual Reasoning.__ 

  _Samira Ebrahimi Kahou, Vincent Michalski, Adam Atkinson, Akos Kadar, Adam Trischler, Yoshua Bengio._ <img src='https://img.shields.io/badge/ICLR_Workshop-2018-yellow'> <a href='https://arxiv.org/abs/1710.07300'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __LEAF-QA: Locate, Encode & Attend for Figure Question Answering.__ 

  _Ritwick Chaudhry, Sumit Shekhar, Utkarsh Gupta, Pranav Maneriker, Prann Bansal, Ajay Joshi._ <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __STL-CQA: Structure-based Transformers with Localization and Encoding for Chart Question Answering.__ 

  _Hrituraj Singh, Sumit Shekhar._ <img src='https://img.shields.io/badge/EMNLP-2020-yellow'> <a href='https://aclanthology.org/2020.emnlp-main.264/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __PlotQA: Reasoning over Scientific Plots.__ 

  _Nitesh Methani, Pritha Ganguly, Mitesh M. Khapra, Pratyush Kumar._ <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://arxiv.org/abs/1909.00997'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __MapQA: A Dataset for Question Answering on Choropleth Maps.__ 

  _Shuaichen Chang, David Palzer, Jialin Li, Eric Fosler-Lussier, Ningchuan Xiao._ <img src='https://img.shields.io/badge/Arxiv-2022-yellow'> <a href='https://arxiv.org/abs/2211.08545'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning.__ 

  _Ahmed Masry, Xuan Long Do, Jia Qing Tan, Shafiq Joty, Enamul Hoque._ <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models.__ 

  _Pan Lu, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, Jianfeng Gao._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2310.02255'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __ChartBench: A Benchmark for Complex Visual Reasoning in Charts.__ 

  _Zhengzhuo Xu, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, Jian Guo._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.15915'><img src='https://img.shields.io/badge/PDF-blue'></a>



**Long-form Questions**  

- __OpenCQA: Open-ended Question Answering with Charts.__ 

  _Shankar Kantharaj, Xuan Long Do, Rixie Tiffany Leong, Jia Qing Tan, Enamul Hoque, Shafiq Joty._ <img src='https://img.shields.io/badge/EMNLP-2022-yellow'> <a href='https://aclanthology.org/2022.emnlp-main.811/'><img src='https://img.shields.io/badge/PDF-blue'></a>

### Chart Captioning (Summarization)

- __Figure Captioning with Relation Maps for Reasoning.__ 

  _Charles Chen, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, Ryan Rossi._ <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model.__ 

  _Jason Obeid, Enamul Hoque._ <img src='https://img.shields.io/badge/INLG-2020-yellow'> <a href='https://aclanthology.org/2020.inlg-1.20/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __SciCap: Generating Captions for Scientific Figures.__ 

  _Ting-Yao Hsu, C Lee Giles, Ting-Hao Huang._ <img src='https://img.shields.io/badge/EMNLP-2021-yellow'> <a href='https://aclanthology.org/2021.findings-emnlp.277/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __Chart-to-Text: A Large-Scale Benchmark for Chart Summarization.__ 

  _Shankar Kantharaj, Rixie Tiffany Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, Shafiq Joty._ <img src='https://img.shields.io/badge/ACL-2022-yellow'> <a href='https://aclanthology.org/2022.acl-long.277/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __LineCap: Line Charts for Data Visualization Captioning Models.__ 

  _Anita Mahinpei, Zona Kostic, Chris Tanner._ <img src='https://img.shields.io/badge/IEEE_VIS-2022-yellow'> <a href='https://ieeexplore.ieee.org/abstract/document/9973197'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __VisText: A Benchmark for Semantically Rich Chart Captioning.__ 

  _Benny Tang, Angie Boggust, Arvind Satyanarayan._ <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.401/'><img src='https://img.shields.io/badge/PDF-blue'></a>

### Chart Caption Factual Error Correction

- __Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.__ 

  _Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a>


### Chart Fact-checking

- __Reading and Reasoning over Chart Images for Evidence-based Automated Fact-Checking.__ 

  _Mubasharar Akhtar, Oana Cocarascu, Elena Simperl._ <img src='https://img.shields.io/badge/EACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-eacl.30/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __ChartCheck: An Evidence-Based Fact-Checking Dataset over Real-World Chart Images.__ 

  _Mubashara Akhtar, Nikesh Subedi, Vivek Gupta, Sahar Tahmasebi, Oana Cocarascu, Elena Simperl._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.07453'><img src='https://img.shields.io/badge/PDF-blue'></a>
  

  
## Methods

### Pre-trained Vision-language Models

- __Enhanced Chart Understanding via Visual Language Pre-training on Plot Table Pairs.__ 

  _Mingyang Zhou, Yi Fung, Long Chen, Christopher Thomas, Heng Ji, Shih-Fu Chang._ <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.85/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __MatCha: Enhancing Visual Language Pretraining with Math Reasoning and Chart Derendering.__

  _Fangyu Liu, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Yasemin Altun, Nigel Collier, Julian Eisenschlos._ <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.714/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __UniChart: A Universal Vision-language Pretrained Model for Chart Comprehension and Reasoning.__

  _Ahmed Masry, Parsa Kavehzadeh, Xuan Long Do, Enamul Hoque, Shafiq Joty._ <img src='https://img.shields.io/badge/EMNLP-2023-yellow'> <a href='https://aclanthology.org/2023.emnlp-main.906/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding.__

  _Kenton Lee, Mandar Joshi, Iulia Raluca Turc, Hexiang Hu, Fangyu Liu, Julian Martin Eisenschlos, Urvashi Khandelwal, Peter Shaw, Ming-Wei Chang, Kristina Toutanova._ <img src='https://img.shields.io/badge/ICML-2023-yellow'> <a href='https://proceedings.mlr.press/v202/lee23g/lee23g.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

### Tool Augmentation
- __DePlot: One-shot visual language reasoning by plot-to-table translation.__

  _Fangyu Liu, Julian Eisenschlos, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Wenhu Chen, Nigel Collier, Yasemin Altun._ <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.660/'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.__

  _Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __Do LLMs Work on Charts? Designing Few-Shot Prompts for Chart Question Answering and Summarization.__

  _Xuan Long Do, Mohammad Hassanpour, Ahmed Masry, Parsa Kavehzadeh, Enamul Hoque, Shafiq Joty._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.10610'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __DOMINO: A Dual-System for Multi-step Visual Language Reasoning.__

  _Peifeng Wang, Olga Golovneva, Armen Aghajanyan, Xiang Ren, Muhao Chen, Asli Celikyilmaz, Maryam Fazel-Zarandi._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2310.02804'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __StructChart: Perception, Structuring, Reasoning for Visual Chart Understanding.__

  _Renqiu Xia, Bo Zhang, Haoyang Peng, Hancheng Ye, Xiangchao Yan, Peng Ye, Botian Shi, Yu Qiao, Junchi Yan._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2309.11268'><img src='https://img.shields.io/badge/PDF-blue'></a>


### Large Vision-language Models

**Tailored for Chart Understanding** 

- __ChartLlama: A Multimodal LLM for Chart Understanding and Generation.__ 

  _Yucheng Han, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, Hanwang Zhang._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.16483'><img src='https://img.shields.io/badge/PDF-blue'></a>
  
- __MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning.__ 

  _Fuxiao Liu, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, Dong Yu._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/PDF-blue'></a>
  
- __ChartAssisstant: A Universal Chart Multimodal Language Model via Chart-to-Table Pre-training and Multitask Instruction Tuning.__ 

  _Fanqing Meng, Wenqi Shao, Quanfeng Lu, Peng Gao, Kaipeng Zhang, Yu Qiao, Ping Luo._ <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2401.02384'><img src='https://img.shields.io/badge/PDF-blue'></a>
  
- __ChartX & ChartVLM: A Versatile Benchmark and Foundation Model for Complicated Chart Reasoning.__ 

  _Renqiu Xia, Bo Zhang, Hancheng Ye, Xiangchao Yan, Qi Liu, Hongbin Zhou, Zijun Chen, Min Dou, Botian Shi, Junchi Yan, Yu Qiao._ <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2402.12185'><img src='https://img.shields.io/badge/PDF-blue'></a>
  
- __ChartInstruct: Instruction Tuning for Chart Comprehension and Reasoning.__ 

  _Ahmed Masry, Mehrad Shahmohammadi, Md Rizwan Parvez, Enamul Hoque, Shafiq Joty._ <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2403.09028'><img src='https://img.shields.io/badge/PDF-blue'></a>
  
- __FigurA11y: AI Assistance for Writing Scientific Alt Text.__ 

  _Nikhil Singh, Andrew Head, Lucy Lu Wang, Jonathan Bragg._ <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://www.llwang.net/assets/pdf/2024_singh_figura11y_iui.pdf'><img src='https://img.shields.io/badge/PDF-blue'></a>

**General-purpose**

- __Visual Instruction Tuning.__ 

  _Haotian Liu, Chunyuan Li, Qingyang Wu, Yong Jae Lee._ <img src='https://img.shields.io/badge/NeurIPS-2023-yellow'> <a href='https://arxiv.org/abs/2304.08485'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __Gemini: A Family of Highly Capable Multimodal Models.__ 

  _Gemini Team Google._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.11805'><img src='https://img.shields.io/badge/PDF-blue'></a>

- __GPT-4V.__ 

  _OpenAI._ <img src='https://img.shields.io/badge/Year-2023-yellow'> <a href='https://openai.com/research/gpt-4v-system-card'><img src='https://img.shields.io/badge/Website-blue'></a>


## Evaluation

### Faithfulness/ Factuality

- __Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning.__ 

  _Kung-Hsiang Huang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, Heng Ji._ <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.10160'><img src='https://img.shields.io/badge/PDF-blue'></a>


## Citation

```bibtex

```
