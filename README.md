# <center>LLM Hallucination Paper List</center>

Below is a list of papers on **LLM hallucination** that I have compiled based on my current readings. It is provided for reference purposes only.

## Survey

1. **Survey of Hallucination in Natural Language Generation** `ACM Computing Surveys 2023 `

   *Ziwei Ji, Nayeon Lee, Rita Frieske, Tiezheng Yu, Dan Su, Yan Xu, Etsuko Ishii, Yejin Bang, Wenliang Dai, Andrea Madotto, Pascale Fung* [[paper]](https://arxiv.org/abs/2202.03629) 2022.02

2. **Siren's Song in the AI Ocean: A Survey on Hallucination in Large Language Models** `arXiv 2023`

   *Yue Zhang, Yafu Li, Leyang Cui, Deng Cai, Lemao Liu, Tingchen Fu, Xinting Huang, Enbo Zhao, Yu Zhang, Yulong Chen, Longyue Wang, Anh Tuan Luu, Wei Bi, Freda Shi, Shuming Shi* [[paper]](https://arxiv.org/abs/2309.01219)

## Causes

1. **On Exposure Bias, Hallucination and Domain Shift in Neural Machine Translation** `ACL 2020`

   *Chaojun Wang, Rico Sennrich* [[paper]](https://aclanthology.org/2020.acl-main.326/) 2020.05

2. **Deduplicating Training Data Makes Language Models Better** `ACL 2022`

   *Katherine Lee, Daphne Ippolito, Andrew Nystrom, Chiyuan Zhang, Douglas Eck, Chris Callison-Burch, Nicholas Carlini* [[paper]](https://aclanthology.org/2022.acl-long.577/) 2021.07

3. **Large Language Models Can Be Easily Distracted by Irrelevant Context** `ICML 2023`

   *Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed Chi, Nathanael Schärli, Denny Zhou* [[paper]](https://proceedings.mlr.press/v202/shi23a/shi23a.pdf) 2023.01

4. **Revisiting the Architectures like Pointer Networks to Efficiently Improve the Next Word Distribution, Summarization Factuality, and Beyond** `ACL 2023 findings`

   *Haw-Shiuan Chang, Zonghai Yao, Alolika Gon, Hong Yu, Andrew McCallum* [[paper]](https://arxiv.org/abs/2305.12289) 2023.03

5. **Why Does ChatGPT Fall Short in Providing Truthful Answers?** `arXiv 2023`

   *Shen Zheng, Jie Huang, Kevin Chen-Chuan Chang* [[paper]](https://arxiv.org/abs/2304.10513) 2023.04

6. **Adaptive Chameleon or Stubborn Sloth: Unraveling the Behavior of Large Language Models in Knowledge Clashes** `arXiv 2023`

   *Jian Xie, Kai Zhang, Jiangjie Chen, Renze Lou, Yu Su* [[paper]](https://arxiv.org/abs/2305.13300) 2023.05

7. **How Language Model Hallucinations Can Snowball** `arXiv 2023`

   *Muru Zhang, Ofir Press, William Merrill, Alisa Liu, Noah A. Smith* [[paper]](https://arxiv.org/abs/2305.13534) 2023.05

8. **Instruction Position Matters in Sequence Generation with Large Language Models** `arXiv 2023`

   *Yijin Liu, Xianfeng Zeng, Fandong Meng, Jie Zhou* [[paper]](https://arxiv.org/abs/2308.12097) 2023.08

9. **Improving Translation Faithfulness of Large Language Models via Augmenting Instructions** `arXiv 2023`

   *Yijie Chen, Yijin Liu, Fandong Meng, Yufeng Chen, Jinan Xu, Jie Zhou* [[paper]](https://arxiv.org/abs/2308.12674) 2023.08

## Detection

1. **SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models** `arXiv 2023`

   *Potsawee Manakul, Adian Liusie, Mark J. F. Gales* [[paper]](https://arxiv.org/abs/2303.08896) 2023.03

2. **The Internal State of an LLM Knows When its Lying** `arXiv 2023`

   *Amos Azaria, Tom Mitchell* [[paper]](https://arxiv.org/abs/2304.13734) 2023.04

3. **LM vs LM: Detecting Factual Errors via Cross Examination** `arXiv 2023`

   *Roi Cohen, May Hamri, Mor Geva, Amir Globerson* [[paper]](https://arxiv.org/abs/2305.13281) 2023.05

4. **Do Language Models Know When They're Hallucinating References?** `arXiv 2023`

   *Ayush Agrawal, Lester Mackey, Adam Tauman Kalai* [[paper]](https://arxiv.org/abs/2305.18248) 2023.05

5. **FActScore: Fine-grained Atomic Evaluation of Factual Precision in Long Form Text Generation** `arXiv 2023`

   *Sewon Min, Kalpesh Krishna, Xinxi Lyu, Mike Lewis, Wen-tau Yih, Pang Wei Koh, Mohit Iyyer, Luke Zettlemoyer, Hannaneh Hajishirzi* [[paper]](https://arxiv.org/abs/2305.14251) 2023.05

6. **Complex Claim Verification with Evidence Retrieved in the Wild** `arXiv 2023`

   *Jifan Chen, Grace Kim, Aniruddh Sriram, Greg Durrett, Eunsol Choi* [[paper]](https://arxiv.org/abs/2305.11859) 2023.05

7. **FACTKG: Fact Verification via Reasoning on Knowledge Graphs** `ACL 2023`

   *Jiho Kim, Sungjin Park, Yeonsu Kwon, Yohan Jo, James Thorne, Edward Choi* [[paper]](https://arxiv.org/abs/2305.06590) 2023.05

8. **Self-Checker: Plug-and-Play Modules for Fact-Checking with Large Language Models** `arXiv 2023`

   *Miaoran Li, Baolin Peng, Zhu Zhang* [[paper]](https://arxiv.org/abs/2305.14623) 2023.05

9. **Retrieving Supporting Evidence for LLMs Generated Answers** `arXiv 2023`

   *Siqing Huo, Negar Arabzadeh, Charles L. A. Clarke* [[paper]](https://arxiv.org/abs/2306.13781) 2023.06

10. **Can LLMs Express Their Uncertainty? An Empirical Evaluation of Confidence Elicitation in LLMs** `arXiv 2023`

   *Miao Xiong, Zhiyuan Hu, Xinyang Lu, Yifei Li, Jie Fu, Junxian He, Bryan Hooi* [[paper]](https://arxiv.org/abs/2306.13063) 2023.06

11. **A Stitch in Time Saves Nine: Detecting and Mitigating Hallucinations of LLMs by Validating Low-Confidence Generation** `arXiv 2023`

    *Neeraj Varshney, Wenlin Yao, Hongming Zhang, Jianshu Chen, Dong Yu* [[paper]](https://arxiv.org/abs/2307.03987) 2023.07

12. **Generating Benchmarks for Factuality Evaluation of Language Models** `arXiv 2023`

    *Dor Muhlgay, Ori Ram, Inbal Magar, Yoav Levine, Nir Ratner, Yonatan Belinkov, Omri Abend, Kevin Leyton-Brown, Amnon Shashua, Yoav Shoham* [[paper]](https://arxiv.org/abs/2307.06908) 2023.07

13. **FacTool: Factuality Detection in Generative AI -- A Tool Augmented Framework for Multi-Task and Multi-Domain Scenarios** `arXiv 2023`

     *I-Chun Chern, Steffi Chern, Shiqi Chen, Weizhe Yuan, Kehua Feng, Chunting Zhou, Junxian He, Graham Neubig, Pengfei Liu* [[paper]](https://arxiv.org/abs/2307.13528) 2023.07

14. **Halo: Estimation and Reduction of Hallucinations in Open-Source Weak Large Language Models** `arXiv 2023`

    *Mohamed Elaraby, Mengyin Lu, Jacob Dunn, Xueying Zhang, Yu Wang, Shizhu Liu* [[paper]](https://arxiv.org/abs/2308.11764) 2023.08

15. **Evaluation of Faithfulness Using the Longest Supported Subsequence** `arXiv 2023`

    *Anirudh Mittal, Timo Schick, Mikel Artetxe, Jane Dwivedi-Yu* [[paper]](https://arxiv.org/abs/2308.12157) 2023.08

16. **Zero-Resource Hallucination Prevention for Large Language Models** `arXiv 2023`

    *Junyu Luo, Cao Xiao, Fenglong Ma* [[paper]](https://arxiv.org/abs/2309.02654) 2023.09

## Mitigation

**Multi-Agent**

1. **MetaGPT: Meta Programming for Multi-Agent Collaborative Framework** `arXiv 2023`

   *Sirui Hong, Xiawu Zheng, Jonathan Chen, Yuheng Cheng, Jinlin Wang, Ceyao Zhang, Zili Wang, Steven Ka Shing Yau, Zijuan Lin, Liyang Zhou, Chenyu Ran, Lingfeng Xiao, Chenglin Wu* [[pdf]](https://arxiv.org/abs/2308.00352) 2023.08

#### Refine

1. **PREFER: Prompt Ensemble Learning via Feedback-Reflect-Refine** `arXiv 2023`

   *Chenrui Zhang, Lin Liu, Jinpeng Wang, Chuyuan Wang, Xiao Sun, Hongyu Wang, Mingchen Cai* [[paper]](https://arxiv.org/abs/2308.12033) 2023.08

#### Retrieval-Augmented LLM

1. **Large Language Models with Controllable Working Memory** `ACL 2023 findings`

   *Daliang Li, Ankit Singh Rawat, Manzil Zaheer, Xin Wang, Michal Lukasik, Andreas Veit, Felix Yu, Sanjiv Kumar* [[paper]](https://arxiv.org/abs/2211.05110) 2022.11

2. **DisentQA: Disentangling Parametric and Contextual Knowledge with Counterfactual Question Answering** `ACL`

   *Ella Neeman, Roee Aharoni, Or Honovich, Leshem Choshen, Idan Szpektor, Omri Abend* [[paper]](https://aclanthology.org/2023.acl-long.559/) 2022.11

3. **Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions** `ACL 2023`

   *Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal* [[paper]](https://arxiv.org/abs/2212.10509) 2022.12

4. **In-Context Retrieval-Augmented Language Models** `TACL 2023`

   *Ori Ram, Yoav Levine, Itay Dalmedigos, Dor Muhlgay, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham* [[paper]](https://arxiv.org/abs/2302.00083) 2023.02

5. **Context-faithful Prompting for Large Language Models** `arXiv 2023`

   *Wenxuan Zhou, Sheng Zhang, Hoifung Poon, Muhao Chen* [[paper]](https://arxiv.org/abs/2303.11315) 2023.03

6. **Search-in-the-Chain: Towards Accurate, Credible and Traceable Large Language Models for Knowledge-intensive Tasks** `arXiv 2023`

   *Shicheng Xu, Liang Pang, Huawei Shen, Xueqi Cheng, Tat-Seng Chua* [[paper]](https://arxiv.org/abs/2304.14732) 2023.04

7. **Verify-and-Edit: A Knowledge-Enhanced Chain-of-Thought Framework** `ACL 2023`

   *Ruochen Zhao, Xingxuan Li, Shafiq Joty, Chengwei Qin, Lidong Bing* [[paper]](https://arxiv.org/abs/2305.03268) 2023.05

8. **Augmented Large Language Models with Parametric Knowledge Guiding** `arXiv 2023`

   *Ziyang Luo, Can Xu, Pu Zhao, Xiubo Geng, Chongyang Tao, Jing Ma, Qingwei Lin, Daxin Jiang* [[paper]](https://arxiv.org/abs/2305.04757) 2023.05

9. **Mitigating Language Model Hallucination with Interactive Question-Knowledge Alignment** `arXiv 2023`

   *Shuo Zhang, Liangming Pan, Junzhou Zhao, William Yang Wang* [[paper]](https://arxiv.org/abs/2305.13669) 2023.05

10. **Query Rewriting for Retrieval-Augmented Large Language Models** `arXiv 2023`

   *Xinbei Ma, Yeyun Gong, Pengcheng He, Hai Zhao, Nan Duan* [[paper]](https://arxiv.org/abs/2305.14283) 2023.05

11. **Enabling Large Language Models to Generate Text with Citations** `arXiv 2023` 

    *Tianyu Gao, Howard Yen, Jiatong Yu, Danqi Chen* [[paper]](https://arxiv.org/abs/2305.14627) 2023.05

11. **Enhancing Retrieval-Augmented Large Language Models with Iterative Retrieval-Generation Synergy** `arXiv 2023`

    *Zhihong Shao, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, Weizhu Chen* [[paper]](https://arxiv.org/abs/2305.15294)

12. **Active Retrieval Augmented Generation** `arXiv 2023`

    *Zhengbao Jiang, Frank F. Xu, Luyu Gao, Zhiqing Sun, Qian Liu, Jane Dwivedi-Yu, Yiming Yang, Jamie Callan, Graham Neubig* [[paper]](https://arxiv.org/abs/2305.06983) 2023.06

13. **Boosting Language Models Reasoning with Chain-of-Knowledge Prompting** `arXiv 2023`

    *Jianing Wang, Qiushi Sun, Nuo Chen, Xiang Li, Ming Gao* [[paper]](https://arxiv.org/abs/2306.06427) 2023.06

14. **Lost in the Middle: How Language Models Use Long Contexts** `arXiv 2023`

    *Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang* [[paper]](https://arxiv.org/abs//2307.03172) 2023.07

15. **Investigating the Factual Knowledge Boundary of Large Language Models with Retrieval Augmentation** `arXiv 2023`

    *Ruiyang Ren, Yuhao Wang, Yingqi Qu, Wayne Xin Zhao, Jing Liu, Hao Tian, Hua Wu, Ji-Rong Wen, Haifeng Wang* [[paper]](https://arxiv.org/abs/2307.11019) 2023.07

11. **MindMap: Knowledge Graph Prompting Sparks Graph of Thoughts in Large Language Models** `arXiv 2023`

    *Yilin Wen, Zifeng Wang, Jimeng Sun* [[paper]](https://arxiv.org/abs/2308.09729) 2023.08

12. **FoodGPT: A Large Language Model in Food Testing Domain with Incremental Pre-training and Knowledge Graph Prompt** `arXiv 2023`

    *Zhixiao Qi, Yijiong Yu, Meiqi Tu, Junyi Tan, Yongfeng Huang* [[paper]](https://arxiv.org/abs/2308.10173) 2023.08

13. **Knowledge-Driven CoT: Exploring Faithful Reasoning in LLMs for Knowledge-intensive Question Answering** `arXiv 2023`

    *Keheng Wang, Feiyu Duan, Sirui Wang, Peiguang Li, Yunsen Xian, Chuantao Yin, Wenge Rong, Zhang Xiong* [[paper]](https://arxiv.org/abs/2308.13259) 2023.08

14. **Optimizing Factual Accuracy in Text Generation through Dynamic Knowledge Selection** `arXiv 2023`

    *Hongjin Qian, Zhicheng Dou, Jiejun Tan, Haonan Chen, Haoqi Gu, Ruofei Lai, Xinyu Zhang, Zhao Cao, Ji-Rong Wen* [[paper]](https://arxiv.org/abs/2308.15711) 2023.08

#### Attributable LLM

1. **RARR: Researching and Revising What Language Models Say, Using Language Models** `ACL 2023`

   *Luyu Gao, Zhuyun Dai, Panupong Pasupat, Anthony Chen, Arun Tejasvi Chaganty, Yicheng Fan, Vincent Y. Zhao, Ni Lao, Hongrae Lee, Da-Cheng Juan, Kelvin Guu* [[paper]](https://arxiv.org/abs/2210.08726) 2022.10

2. **Attributed Question Answering: Evaluation and Modeling for Attributed Large Language Models** `arXiv 2022`

   *Bernd Bohnet, Vinh Q. Tran, Pat Verga, Roee Aharoni, Daniel Andor, Livio Baldini Soares, Massimiliano Ciaramita, Jacob Eisenstein, Kuzman Ganchev, Jonathan Herzig, Kai Hui, Tom Kwiatkowski, Ji Ma, Jianmo Ni, Lierni Sestorain Saralegui, Tal Schuster, William W. Cohen, Michael Collins, Dipanjan Das, Donald Metzler, Slav Petrov, Kellie Webster* [[paper]](https://arxiv.org/abs/2212.08037) 2022.12

3. **Characterizing Attribution and Fluency Tradeoffs for Retrieval-Augmented Large Language Models** `arXiv 2023`

   *Renat Aksitov, Chung-Ching Chang, David Reitter, Siamak Shakeri, Yunhsuan Sung* [[paper]](https://arxiv.org/abs/2302.05578) 2023.02

4. **Evaluating Verifiability in Generative Search Engines** `arXiv 2023`

   *Nelson F. Liu, Tianyi Zhang, Percy Liang* [[paper]](https://arxiv.org/abs/2304.09848) 2023.04

5. **WebBrain: Learning to Generate Factually Correct Articles for Queries by Grounding on Large Web Corpus** `arXiv 2023`

   *Hongjing Qian, Yutao Zhu, Zhicheng Dou, Haoqi Gu, Xinyu Zhang, Zheng Liu, Ruofei Lai, Zhao Cao, Jian-Yun Nie, Ji-Rong Wen* [[paper]](https://arxiv.org/abs/2304.04358) 2023.04

6. **Automatic Evaluation of Attribution by Large Language Models** `arXiv 2023`

   *Xiang Yue, Boshi Wang, Kai Zhang, Ziru Chen, Yu Su, Huan Sun* [[paper]](https://arxiv.org/abs/2305.06311) 2023.05

7. **Enabling Large Language Models to Generate Text with Citations** `arXiv 2023`

   *Tianyu Gao, Howard Yen, Jiatong Yu, Danqi Chen* [[paper]](https://arxiv.org/abs/2305.14627) 2023.05

8. **PURR: Efficiently Editing Language Model Hallucinations by Denoising Language Model Corruptions** `arXiv 2023`

   *Anthony Chen, Panupong Pasupat, Sameer Singh, Hongrae Lee, Kelvin Guu* [[paper]](https://arxiv.org/abs/2305.14908) 2023.05

9. **RefGPT: Reference -> Truthful & Customized Dialogues Generation by GPTs and for GPTs** `arXiv 2023`

   *Dongjie Yang, Ruifeng Yuan, YuanTao Fan, YiFei Yang, Zili Wang, Shusen Wang, Hai Zhao* [[paper]](https://arxiv.org/abs/2305.14994) 2023.05

10. **Large Language Models are Built-in Autoregressive Search Engines** `ACL 2023 findings`

   *Noah Ziems, Wenhao Yu, Zhihan Zhang, Meng Jiang* [[paper]](https://aclanthology.org/2023.findings-acl.167.pdf)

11. **Citation: A Key to Building Responsible and Accountable Large Language Models** `arXiv 2023`

   *Jie Huang, Kevin Chen-Chuan Chang* [[paper]](https://arxiv.org/abs/2307.02185) 2023.07

11. **HAGRID: A Human-LLM Collaborative Dataset for Generative Information-Seeking with Attribution** `arXiv 2023`

    *Ehsan Kamalloo, Aref Jafari, Xinyu Zhang, Nandan Thakur, Jimmy Lin* [[paper]](https://arxiv.org/abs/2307.16883) 2023.07

#### Decoding

1. **Sticking to the Facts: Confident Decoding for Faithful Data-to-Text Generation** `arXiv 2019`

   *Ran Tian, Shashi Narayan, Thibault Sellam, Ankur P. Parikh* [[paper]](https://arxiv.org/abs/1910.08684)

2. **Trading Off Diversity and Quality in Natural Language Generation** `HumEval 2021`

   *Hugh Zhang, Daniel Duckworth, Daphne Ippolito, Arvind Neelakantan* [[paper]](https://aclanthology.org/2021.humeval-1.3/)

3. **Contrastive Decoding: Open-ended Text Generation as Optimization** `ACL 2023`

   *Xiang Lisa Li, Ari Holtzman, Daniel Fried, Percy Liang, Jason Eisner, Tatsunori Hashimoto, Luke Zettlemoyer, Mike Lewis* [[paper]](https://arxiv.org/abs/2210.15097)

4. **Look-back Decoding for Open-Ended Text Generation** `arXiv 2023`

   *Nan Xu, Chunting Zhou, Asli Celikyilmaz, Xuezhe Ma* [[paper]](https://arxiv.org/abs/2305.13477) 2023.05

5. **Trusting Your Evidence: Hallucinate Less with Context-aware Decoding** `arXiv 2023`

   *Weijia Shi, Xiaochuang Han, Mike Lewis, Yulia Tsvetkov, Luke Zettlemoyer, Scott Wen-tau Yih* [[paper]](https://arxiv.org/abs/2305.14739) 2023.05

6. **KL-Divergence Guided Temperature Sampling** `arXiv 2023`

   *Chung-Ching Chang, David Reitter, Renat Aksitov, Yun-Hsuan Sung* [[paper]](https://arxiv.org/abs/2306.01286) 2023.06

7. **Improving Code Generation by Dynamic Temperature Sampling** `arXiv 2023`

   *Yuqi Zhu, Jia Allen Li, Ge Li, YunFei Zhao, Jia Li, Zhi Jin, Hong Mei* [[paper]](https://arxiv.org/abs/2309.02772) 2023.09

## Evaluation

1. **A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity** `arXiv 2023`

   *Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung* [[paper]](https://arxiv.org/abs/2302.04023) 2023.02

2. **Hallucinations in Large Multilingual Translation Models** `arXiv 2023`

   *Nuno M. Guerreiro, Duarte Alves, Jonas Waldendorf, Barry Haddow, Alexandra Birch, Pierre Colombo, André F. T. Martins* [[paper]](https://arxiv.org/abs/2303.16104) 2023.03

3. **Evaluating Correctness and Faithfulness of Instruction-Following Models for Question Answering** `arXiv 2023`

   *Vaibhav Adlakha, Parishad BehnamGhader, Xing Han Lu, Nicholas Meade, Siva Reddy* [[paper]](https://arxiv.org/abs/2307.16877) 2023.07

4. **Challenges and Applications of Large Language Models** `arXiv 2023`

   *Jean Kaddour, Joshua Harris, Maximilian Mozes, Herbie Bradley, Roberta Raileanu, Robert McHardy* [[paper]](https://arxiv.org/abs/2307.10169)

5. **Head-to-Tail: How Knowledgeable are Large Language Models (LLM)? A.K.A. Will LLMs Replace Knowledge Graphs?** `arXiv 2023`

   *Kai Sun, Yifan Ethan Xu, Hanwen Zha, Yue Liu, Xin Luna Dong* [[paper]](https://arxiv.org/abs/2308.10168) 2023.08

## Benchmark

1. **TruthfulQA: Measuring How Models Mimic Human Falsehoods** `ACL 2022`

   *Stephanie Lin, Jacob Hilton, Owain Evans* [[paper]](https://arxiv.org/abs/2109.07958) 2021.09

2. **HalOmi: A Manually Annotated Benchmark for Multilingual Hallucination and Omission Detection in Machine Translation** `arXiv 2023`

   *David Dale, Elena Voita, Janice Lam, Prangthip Hansanti, Christophe Ropers, Elahe Kalbassi, Cynthia Gao, Loïc Barrault, Marta R. Costa-jussà* [[paper]](https://arxiv.org/abs/2305.11746) 2023.05

3. **HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models** `arXiv 2023`

   *Junyi Li, Xiaoxue Cheng, Wayne Xin Zhao, Jian-Yun Nie, Ji-Rong Wen* [[paper]](https://arxiv.org/abs/2305.11747) 2023.05

## MultiModal

1. **End-to-End Multimodal Fact-Checking and Explanation Generation: A Challenging Dataset and Models** `SIGIR 2023`

   *Barry Menglong Yao, Aditya Shah, Lichao Sun, Jin-Hee Cho, Lifu Huang* [[paper]](https://arxiv.org/abs/2205.12487) 2022.05
   
1. **Evaluation and Analysis of Hallucination in Large Vision-Language Models** `arXiv 2023`

   *Junyang Wang, Yiyang Zhou, Guohai Xu, Pengcheng Shi, Chenlin Zhao, Haiyang Xu, Qinghao Ye, Ming Yan, Ji Zhang, Jihua Zhu, Jitao Sang, Haoyu Tang* [[paper]](https://arxiv.org/abs/2308.15126) 2023.08