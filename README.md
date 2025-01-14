# Awesome Large Language Model Unlearning

<p align="center">
<a href=""> <img src="https://awesome.re/badge-flat.svg" alt="Awesome"></a>
<a href=""> <img src="https://img.shields.io/github/stars/chrisliu298/awesome-llm-unlearning?style=flat-square&logo=github" alt="GitHub stars"></a>
<a href=""> <img src="https://img.shields.io/github/forks/chrisliu298/awesome-llm-unlearning?style=flat-square&logo=github" alt="GitHub forks"></a>
<a href=""> <img src="https://img.shields.io/github/issues/chrisliu298/awesome-llm-unlearning?style=flat-square&logo=github" alt="GitHub issues"></a>
<a href=""> <img src="https://img.shields.io/github/last-commit/chrisliu298/awesome-llm-unlearning?style=flat-square&logo=github" alt="GitHub Last commit"></a>
</p>

This repository tracks the latest research on machine unlearning in large language models (LLMs). The goal is to offer a comprehensive list of papers, datasets, and resources relevant to the topic.

> [!NOTE]
> If you believe your paper on LLM unlearning is not included, or if you find a mistake, typo, or information that is not up to date, please open an issue, and I will address it as soon as possible.
>
> If you want to add a new paper, feel free to either open an issue or create a pull request.

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Papers](#papers)
  - [Methods](#methods)
  - [Surveys and Position Papers](#surveys-and-position-papers)
- [Blog Posts](#blog-posts)
- [Datasets](#datasets)

## Papers

### Methods

- [Unlearning Climate Misinformation in Large Language Models](https://arxiv.org/abs/2405.19563)
  - Author(s): Michael Fore, Simranjit Singh, Chaehong Lee, Amritanshu Pandey, Antonios Anastasopoulos, Dimitrios Stamoulis
  - Date: 2024-05
  - Venue: -
  - Code: -
- [Large Scale Knowledge Washing](https://arxiv.org/abs/2405.16720)
  - Author(s): Yu Wang, Ruihan Wu, Zexue He, Xiusi Chen, Julian McAuley
  - Date: 2024-05
  - Venue: -
  - Code: [GitHub](https://github.com/wangyu-ustc/LargeScaleWashing)
- [Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://arxiv.org/abs/2405.12523)
  - Author(s): Jiaqi Li, Qianshan Wei, Chuanyi Zhang, Guilin Qi, Miaozeng Du, Yongrui Chen, Sheng Bi
  - Date: 2024-05
  - Venue: -
  - Code: -
- [To Each (Textual Sequence) Its Own: Improving Memorized-Data Unlearning in Large Language Models](https://arxiv.org/abs/2405.03097)
  - Author(s): George-Octavian Barbulescu, Peter Triantafillou
  - Date: 2024-05
  - Venue: ICML 2024
  - Code: -
- [SOUL: Unlocking the Power of Second-Order Optimization for LLM Unlearning](https://arxiv.org/abs/2404.18239)
  - Author(s): Jinghan Jia, Yihua Zhang, Yimeng Zhang, Jiancheng Liu, Bharat Runwal, James Diffenderfer, Bhavya Kailkhura, Sijia Liu
  - Date: 2024-04
  - Venue: -
  - Code: [GitHub](https://github.com/OPTML-Group/SOUL)
- [Machine Unlearning in Large Language Models](https://arxiv.org/abs/2404.16841)
  - Author(s): Kongyang Chen, Zixin Wang, Bing Mi, Waixi Liu, Shaowei Wang, Xiaojun Ren, Jiaxing Shen
  - Date: 2024-04
  - Venue: -
  - Code: -
- [Offset Unlearning for Large Language Models](https://arxiv.org/abs/2404.11045)
  - Author(s): James Y. Huang, Wenxuan Zhou, Fei Wang, Fred Morstatter, Sheng Zhang, Hoifung Poon, Muhao Chen
  - Date: 2024-04
  - Venue: -
  - Code: [GitHub](https://github.com/luka-group/Delta-Unlearning)
- [Eraser: Jailbreaking Defense in Large Language Models via Unlearning Harmful Knowledge](https://arxiv.org/abs/2404.05880)
  - Author(s): Weikai Lu, Ziqian Zeng, Jianwei Wang, Zhengdong Lu, Zelin Chen, Huiping Zhuang, Cen Chen
  - Date: 2024-04
  - Venue: -
  - Code: -
- [Negative Preference Optimization: From Catastrophic Collapse to Effective Unlearning](https://arxiv.org/abs/2404.05868)
  - Author(s): Ruiqi Zhang, Licong Lin, Yu Bai, Song Mei
  - Date: 2024-04
  - Venue: -
  - Code: [GitHub](https://github.com/licong-lin/negative-preference-optimization)
- [Localizing Paragraph Memorization in Language Models](https://arxiv.org/abs/2403.19851)
  - Author(s): Niklas Stoehr, Mitchell Gordon, Chiyuan Zhang, Owen Lewis
  - Date: 2024-03
  - Venue: -
  - Code: -
- [The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning](https://arxiv.org/abs/2403.03218)
  - Author(s): Nathaniel Li, Alexander Pan, Anjali Gopal, Summer Yue, Daniel Berrios, Alice Gatti, Justin D. Li, Ann-Kathrin Dombrowski, Shashwat Goel, Long Phan, Gabriel Mukobi, Nathan Helm-Burger, Rassin Lababidi, Lennart Justen, Andrew B. Liu, Michael Chen, Isabelle Barrass, Oliver Zhang, Xiaoyuan Zhu, Rishub Tamirisa, Bhrugu Bharathi, Adam Khoja, Zhenqi Zhao, Ariel Herbert-Voss, Cort B. Breuer, Samuel Marks, Oam Patel, Andy Zou, Mantas Mazeika, Zifan Wang, Palash Oswal, Weiran Lin, Adam A. Hunt, Justin Tienken-Harder, Kevin Y. Shih, Kemper Talley, John Guan, Russell Kaplan, Ian Steneker, David Campbell, Brad Jokubaitis, Alex Levinson, Jean Wang, William Qian, Kallol Krishna Karmakar, Steven Basart, Stephen Fitz, Mindy Levine, Ponnurangam Kumaraguru, Uday Tupakula, Vijay Varadharajan, Ruoyu Wang, Yan Shoshitaishvili, Jimmy Ba, Kevin M. Esvelt, Alexandr Wang, Dan Hendrycks
  - Date: 2024-03
  - Venue: -
  - Code: [GitHub](https://github.com/centerforaisafety/wmdp)
- [Dissecting Language Models: Machine Unlearning via Selective Pruning](https://arxiv.org/abs/2403.01267)
  - Author(s): Nicholas Pochinkov, Nandi Schoots
  - Date: 2024-03
  - Venue: -
  - Code: -
- [Second-Order Information Matters: Revisiting Machine Unlearning for Large Language Models](https://arxiv.org/abs/2403.10557)
  - Author(s): Kang Gu, Md Rafi Ur Rashid, Najrin Sultana, Shagufta Mehnaz
  - Date: 2024-03
  - Venue: -
  - Code: -
- [Ethos: Rectifying Language Models in Orthogonal Parameter Space](https://arxiv.org/abs/2403.08994)
  - Author(s): Lei Gao, Yue Niu, Tingting Tang, Salman Avestimehr, Murali Annavaram
  - Date: 2024-03
  - Venue: -
  - Code: -
- [Towards Efficient and Effective Unlearning of Large Language Models for Recommendation](https://arxiv.org/abs/2403.03536)
  - Author(s): Hangyu Wang, Jianghao Lin, Bo Chen, Yang Yang, Ruiming Tang, Weinan Zhang, Yong Yu
  - Date: 2024-03
  - Venue: -
  - Code: [GitHub](https://github.com/justarter/E2URec)
- [Guardrail Baselines for Unlearning in LLMs](https://arxiv.org/abs/2403.03329)
  - Author(s): Pratiksha Thaker, Yash Maurya, Virginia Smith
  - Date: 2024-03
  - Venue: ICLR 2024 SeT-LLM Workshop
  - Code: -
- [Deciphering the Impact of Pretraining Data on Large Language Models through Machine Unlearning](https://arxiv.org/abs/2402.11537)
  - Author(s): Deciphering the Impact of Pretraining Data on Large Language Models through Machine Unlearning
  - Date: 2024-02
  - Venue: -
  - Code: -
- [Unmemorization in Large Language Models via Self-Distillation and Deliberate Imagination](https://arxiv.org/abs/2402.10052)
  - Author(s): Yijiang River Dong, Hongzhou Lin, Mikhail Belkin, Ramon Huerta, Ivan Vulić
  - Date: 2024-02
  - Venue: -
  - Code: [GitHub](https://github.com/dong-river/LLM_unlearning)
- [Towards Safer Large Language Models through Machine Unlearning](https://arxiv.org/abs/2402.10058)
  - Author(s): Zheyuan Liu, Guangyao Dou, Zhaoxuan Tan, Yijun Tian, Meng Jiang
  - Date: 2024-02
  - Venue: -
  - Code: [GitHub](https://github.com/franciscoliu/SKU)
- [Selective Forgetting: Advancing Machine Unlearning Techniques and Evaluation in Language Models](https://arxiv.org/abs/2402.05813)
  - Author(s): Lingzhi Wang, Xingshan Zeng, Jinsong Guo, Kam-Fai Wong, Georg Gottlob
  - Date: 2024-02
  - Venue: -
  - Code: -
- [Unlearnable Algorithms for In-context Learning](https://arxiv.org/abs/2402.00751)
  - Author(s): Andrei Muresanu, Anvith Thudi, Michael R. Zhang, Nicolas Papernot
  - Date: 2024-02
  - Venue: -
  - Code: -
- [Machine Unlearning of Pre-trained Large Language Models](https://arxiv.org/abs/2402.15159)
  - Author(s): Jin Yao, Eli Chien, Minxin Du, Xinyao Niu, Tianhao Wang, Zezhou Cheng, Xiang Yue
  - Date: 2024-02
  - Venue: -
  - Code: [GitHub](https://github.com/yaojin17/Unlearning_LLM)
- [Visual In-Context Learning for Large Vision-Language Models](https://arxiv.org/abs/2402.11574)
  - Author(s): Yucheng Zhou, Xiang Li, Qianning Wang, Jianbing Shen
  - Date: 2024-02
  - Venue: -
  - Code: -
- [EFUF: Efficient Fine-grained Unlearning Framework for Mitigating Hallucinations in Multimodal Large Language Models](https://arxiv.org/abs/2402.09801)
  - Author(s): Shangyu Xing, Fei Zhao, Zhen Wu, Tuo An, Weihao Chen, Chunhui Li, Jianbing Zhang, Xinyu Dai
  - Date: 2024-02
  - Venue: -
  - Code: -
- [Unlearning Reveals the Influential Training Data of Language Models](https://arxiv.org/abs/2401.15241)
  - Author(s): Masaru Isonuma, Ivan Titov
  - Date: 2024-01
  - Venue: -
  - Code: -
- [TOFU: A Task of Fictitious Unlearning for LLMs](https://arxiv.org/abs/2401.06121)
  - Author(s): Pratyush Maini, Zhili Feng, Avi Schwarzschild, Zachary C. Lipton, J. Zico Kolter
  - Date: 2024-01
  - Venue: -
  - Code: [GitHub](https://github.com/locuslab/tofu)
- [FairSISA: Ensemble Post-Processing to Improve Fairness of Unlearning in LLMs](https://arxiv.org/abs/2312.07420)
  - Author(s): Swanand Ravindra Kadhe, Anisa Halimi, Ambrish Rawat, Nathalie Baracaldo
  - Date: 2023-12
  - Venue: NeurIPS 2023 SoLaR Workshop
  - Code: -
- [Making Harmful Behaviors Unlearnable for Large Language Models](https://arxiv.org/abs/2311.02105)
  - Author(s): Xin Zhou, Yi Lu, Ruotian Ma, Tao Gui, Qi Zhang, Xuanjing Huang
  - Date: 2023-11
  - Venue: -
  - Code: -
- [Forgetting before Learning: Utilizing Parametric Arithmetic for Knowledge Updating in Large Language Models](https://arxiv.org/abs/2311.08011)
  - Author(s): Shiwen Ni, Dingwei Chen, Chengming Li, Xiping Hu, Ruifeng Xu, Min Yang
  - Date: 2023-11
  - Venue: -
  - Code: -
- [Who's Harry Potter? Approximate Unlearning in LLMs](https://arxiv.org/abs/2310.02238)
  - Author(s): Ronen Eldan, Mark Russinovich
  - Date: 2023-10
  - Venue: -
  - Code: -
- [DEPN: Detecting and Editing Privacy Neurons in Pretrained Language Models](https://arxiv.org/abs/2310.20138)
  - Author(s): Xinwei Wu, Junzhuo Li, Minghui Xu, Weilong Dong, Shuangzhi Wu, Chao Bian, Deyi Xiong
  - Date: 2023-10
  - Venue: EMNLP 2023
  - Code: [GitHub](https://github.com/flamewei123/DEPN)
- [Unlearn What You Want to Forget: Efficient Unlearning for LLMs](https://aclanthology.org/2023.emnlp-main.738/)
  - Author(s): Jiaao Chen, Diyi Yang
  - Date: 2023-10
  - Venue: EMNLP 2023
  - Code: [GitHub](https://github.com/SALT-NLP/Efficient_Unlearning/)
- [In-Context Unlearning: Language Models as Few Shot Unlearners](https://arxiv.org/abs/2310.07579)
  - Author(s): Martin Pawelczyk, Seth Neel, Himabindu Lakkaraju
  - Date: 2023-10
  - Venue: -
  - Code: -
- [Large Language Model Unlearning](https://arxiv.org/abs/2310.10683)
  - Author(s): Yuanshun Yao, Xiaojun Xu, Yang Liu
  - Date: 2023-10
  - Venue: NeurIPS 2023 SoLaR Workshop
  - Code: [GitHub](https://github.com/kevinyaobytedance/llm_unlearn)
- [Forgetting Private Textual Sequences in Language Models via Leave-One-Out Ensemble](https://arxiv.org/abs/2309.16082)
  - Author(s): Zhe Liu, Ozlem Kalinli
  - Date: 2023-09
  - Venue: -
  - Code: -
- [Can Sensitive Information Be Deleted From LLMs? Objectives for Defending Against Extraction Attacks](https://arxiv.org/abs/2309.17410)
  - Author(s): Vaidehi Patil, Peter Hase, Mohit Bansal
  - Date: 2023-09
  - Venue: -
  - Code: [GitHub](https://github.com/Vaidehi99/InfoDeletionAttacks)
- [Separate the Wheat from the Chaff: Model Deficiency Unlearning via Parameter-Efficient Module Operation](https://arxiv.org/abs/2308.08090)
  - Author(s): Xinshuo Hu, Dongfang Li, Baotian Hu, Zihao Zheng, Zhenyu Liu, Min Zhang
  - Date: 2023-08
  - Venue: AAAI 2024
  - Code: [GitHub](https://github.com/HITsz-TMG/Ext-Sub)
- [Unlearning Bias in Language Models by Partitioning Gradients](https://aclanthology.org/2023.findings-acl.375/)
  - Author(s): Charles Yu, Sullam Jeoung, Anish Kasi, Pengfei Yu, Heng Ji
  - Date: 2023-07
  - Venue: ACL (Findings) 2023
  - Code: [GitHub](https://github.com/CharlesYu2000/PCGU-UnlearningBias)
- [Make Text Unlearnable: Exploiting Effective Patterns to Protect Personal Data](https://arxiv.org/abs/2307.00456)
  - Author(s): Xinzhe Li, Ming Liu, Shang Gao
  - Date: 2023-07
  - Venue: -
  - Code: -
- [What can we learn from Data Leakage and Unlearning for Law?](https://arxiv.org/abs/2307.10476)
  - Author(s): Jaydeep Borkar
  - Date: 2023-07
  - Venue: -
  - Code: -
- [LEACE: Perfect linear concept erasure in closed form](https://arxiv.org/abs/2306.03819)
  - Author(s): Nora Belrose, David Schneider-Joseph, Shauli Ravfogel, Ryan Cotterell, Edward Raff, Stella Biderman
  - Date: 2023-06
  - Venue: NeurIPS 2023
  - Code: [GitHub](https://github.com/EleutherAI/concept-erasure)
- [Composing Parameter-Efficient Modules with Arithmetic Operations](https://arxiv.org/abs/2306.14870)
  - Author(s): Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He
  - Date: 2023-06
  - Venue: NeurIPS 2023
  - Code: [GitHub](https://github.com/hkust-nlp/PEM_composition)
- [KGA: A General Machine Unlearning Framework Based on Knowledge Gap Alignment](https://arxiv.org/abs/2305.06535)
  - Author(s): Lingzhi Wang, Tong Chen, Wei Yuan, Xingshan Zeng, Kam-Fai Wong, Hongzhi Yin
  - Date: 2023-05
  - Venue: -
  - Code: [GitHub](https://github.com/Lingzhi-WANG/KGAUnlearn)
- [Editing Models with Task Arithmetic](https://arxiv.org/abs/2212.04089)
  - Author(s): Gabriel Ilharco, Marco Tulio Ribeiro, Mitchell Wortsman, Suchin Gururangan, Ludwig Schmidt, Hannaneh Hajishirzi, Ali Farhadi
  - Date: 2022-12
  - Venue: ICLR 2023
  - Code: [GitHub](https://github.com/mlfoundations/task_vectors)
- [Privacy Adhering Machine Un-learning in NLP](https://arxiv.org/abs/2212.09573)
  - Author(s): Vinayshekhar Bannihatti Kumar, Rashmi Gangadharaiah, Dan Roth
  - Date: 2022-12
  - Venue: -
  - Code: -
- [The CRINGE Loss: Learning what language not to model](https://arxiv.org/abs/2211.05826)
  - Author(s): Leonard Adolphs, Tianyu Gao, Jing Xu, Kurt Shuster, Sainbayar Sukhbaatar, Jason Weston
  - Date: 2022-11
  - Venue: -
  - Code: -
- [Knowledge Unlearning for Mitigating Privacy Risks in Language Models](https://arxiv.org/abs/2210.01504)
  - Author(s): Joel Jang, Dongkeun Yoon, Sohee Yang, Sungmin Cha, Moontae Lee, Lajanugen Logeswaran, Minjoon Seo
  - Date: 2022-10
  - Venue: -
  - Code: [GitHub](https://github.com/joeljang/knowledge-unlearning)
- [Quark: Controllable Text Generation with Reinforced Unlearning](https://arxiv.org/abs/2205.13636)
  - Author(s): Ximing Lu, Sean Welleck, Jack Hessel, Liwei Jiang, Lianhui Qin, Peter West, Prithviraj Ammanabrolu, Yejin Choi
  - Date: 2022-05
  - Venue: NeurIPS 2022
  - Code: [GitHub](https://github.com/GXimingLu/Quark)
- [DExperts: Decoding-Time Controlled Text Generation with Experts and Anti-Experts](https://arxiv.org/abs/2105.03023)
  - Author(s): Alisa Liu, Maarten Sap, Ximing Lu, Swabha Swayamdipta, Chandra Bhagavatula, Noah A. Smith, Yejin Choi
  - Date: 2021-05
  - Venue: ACL 2021
  - Code: [GitHub](https://github.com/alisawuffles/DExperts)

### Surveys and Position Papers

- [Digital Forgetting in Large Language Models: A Survey of Unlearning Methods](https://arxiv.org/abs/2404.02062)
  - Author(s): Alberto Blanco-Justicia, Najeeb Jebreel, Benet Manzanares, David Sánchez, Josep Domingo-Ferrer, Guillem Collell, Kuan Eeik Tan
  - Date: 2024-04
  - Venue: -
- [Machine Unlearning for Traditional Models and Large Language Models: A Short Survey](https://arxiv.org/abs/2404.01206)
  - Author(s): Yi Xu
  - Date: 2024-04
  - Venue: -
- [The Frontier of Data Erasure: Machine Unlearning for Large Language Models](https://arxiv.org/abs/2403.15779)
  - Author(s): Youyang Qu, Ming Ding, Nan Sun, Kanchana Thilakarathna, Tianqing Zhu, Dusit Niyato
  - Date: 2024-03
  - Venue: -
- [Rethinking Machine Unlearning for Large Language Models](https://arxiv.org/abs/2402.08787)
  - Author(s): Sijia Liu, Yuanshun Yao, Jinghan Jia, Stephen Casper, Nathalie Baracaldo, Peter Hase, Xiaojun Xu, Yuguang Yao, Hang Li, Kush R. Varshney, Mohit Bansal, Sanmi Koyejo, Yang Liu
  - Date: 2024-02
  - Venue: -
- [Eight Methods to Evaluate Robust Unlearning in LLMs](https://arxiv.org/abs/2402.16835)
  - Author(s): Aengus Lynch, Phillip Guo, Aidan Ewart, Stephen Casper, Dylan Hadfield-Menell
  - Date: 2024-02
  - Venue: -
- [Knowledge Unlearning for LLMs: Tasks, Methods, and Challenges](https://arxiv.org/abs/2311.15766)
  - Author(s): Nianwen Si, Hao Zhang, Heyu Chang, Wenlin Zhang, Dan Qu, Weiqiang Zhang
  - Date: 2023-11
  - Venue: -
- [Right to be Forgotten in the Era of Large Language Models: Implications, Challenges, and Solutions](https://arxiv.org/abs/2307.03941)
  - Author(s): Dawen Zhang, Pamela Finckenberg-Broman, Thong Hoang, Shidong Pan, Zhenchang Xing, Mark Staples, Xiwei Xu
  - Date: 2023-07
  - Venue: -

## Blog Posts

- [Machine Unlearning in 2024](https://ai.stanford.edu/~kzliu/blog/unlearning)
  - Author(s): [Ken Liu](https://ai.stanford.edu/~kzliu/)
  - Date: 2024-05
- [Deep Forgetting & Unlearning for Safely-Scoped LLMs](https://www.alignmentforum.org/posts/mFAvspg4sXkrfZ7FA/deep-forgetting-and-unlearning-for-safely-scoped-llms)
  - Author(s): [Stephen Casper](https://stephencasper.com/)
  - Date: 2023-12

## Datasets

- TOFU
  - Description: A synthetic QA dataset of fictitious authors generated by GPT-4. The datasets comes with three splits of the retain/forget sets, including 99/1, 95/5, and 90/10 (in percentage). The dataset also includes questions about real authors and world facts to evaluate the loss of general knowledge after unlearning.
  - Links: [arXiv](https://arxiv.org/abs/2401.06121), [Hugging Face](https://huggingface.co/datasets/locuslab/TOFU)
- WMDP
  - Description: A benchmark for assessing hazardous knowledge in biology, chemistry, and cybersecurity, containing about 4000 multiple-choice questions with similar style to MMLU. It also comes with corpora in the three domains.
  - Links: [arXiv](https://arxiv.org/abs/2403.03218), [Hugging Face](https://huggingface.co/datasets/cais/wmdp)
- MMLU Subsets
  - Description: A task proposed along with the WMDP dataset. The goal is to unlearn (retain) three categories in the [MMLU](https://arxiv.org/abs/2009.03300) dataset: economics (econometrics and others), physics (math and others), and law (jurisprudence and others). The task requires high-precision unlearning, because the retain sets are categories closely related to the unlearning categories.
  - Links: [arXiv](https://arxiv.org/abs/2009.03300), [Hugging Face](https://huggingface.co/datasets/cais/mmlu)
- arXiv, GitHub, and copyrighted books corpus
  - Description: A dataset for evaluating approximate unlearning algorithms for pre-trained LLMs. The dataset contains both forget and retain splits of each category, and comes with both in-distribution and general retain sets. The dataset is deisgned for unlearning directly on pre-trained models, as they are random samples from the pre-training dataset of [Yi](https://arxiv.org/abs/2403.04652).
  - Links: [arXiv](https://arxiv.org/abs/2402.15159), [Hugging Face](https://huggingface.co/datasets/llmunlearn/unlearn_dataset)
