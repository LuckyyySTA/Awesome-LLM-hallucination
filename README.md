# <center>LLM Hallucination Paper List</center>

Below is a list of papers on **LLM hallucination** that I have compiled based on my current readings. It is provided for reference purposes only.

## Survey

1. **Survey of Hallucination in Natural Language Generation** `ACM Computing Surveys 2023 `

   *Ziwei Ji, Nayeon Lee, Rita Frieske, Tiezheng Yu, Dan Su, Yan Xu, Etsuko Ishii, Yejin Bang, Wenliang Dai, Andrea Madotto, Pascale Fung* [[paper]](https://arxiv.org/abs/2202.03629) 2022.02

## Causes

1. **On Exposure Bias, Hallucination and Domain Shift in Neural Machine Translation** `ACL 2020`

   *Chaojun Wang, Rico Sennrich* [[paper]](https://aclanthology.org/2020.acl-main.326/) 2020.05

2. **Deduplicating Training Data Makes Language Models Better** `ACL 2022`

   *Katherine Lee, Daphne Ippolito, Andrew Nystrom, Chiyuan Zhang, Douglas Eck, Chris Callison-Burch, Nicholas Carlini* [[paper]](https://aclanthology.org/2022.acl-long.577/) 2021.07

3. **Revisiting the Architectures like Pointer Networks to Efficiently Improve the Next Word Distribution, Summarization Factuality, and Beyond** `ACL 2023 findings`

   *Haw-Shiuan Chang, Zonghai Yao, Alolika Gon, Hong Yu, Andrew McCallum* [[paper]](https://arxiv.org/abs/2305.12289) 2023.03

4. **Why Does ChatGPT Fall Short in Providing Truthful Answers?** `arXiv 2023`

   *Shen Zheng, Jie Huang, Kevin Chen-Chuan Chang* [[paper]](https://arxiv.org/abs/2304.10513) 2023.04

5. **Adaptive Chameleon or Stubborn Sloth: Unraveling the Behavior of Large Language Models in Knowledge Clashes** `arXiv 2023`

   *Jian Xie, Kai Zhang, Jiangjie Chen, Renze Lou, Yu Su* [[paper]](https://arxiv.org/abs/2305.13300) 2023.05

6. **How Language Model Hallucinations Can Snowball** `arXiv 2023`

   *Muru Zhang, Ofir Press, William Merrill, Alisa Liu, Noah A. Smith* [[paper]](https://arxiv.org/abs/2305.13534) 2023.05

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

6. **Retrieving Supporting Evidence for LLMs Generated Answers** `arXiv 2023`

   *Siqing Huo, Negar Arabzadeh, Charles L. A. Clarke* [[paper]](https://arxiv.org/abs/2306.13781) 2023.06

7. **A Stitch in Time Saves Nine: Detecting and Mitigating Hallucinations of LLMs by Validating Low-Confidence Generation** `arXiv 2023`

   *Neeraj Varshney, Wenlin Yao, Hongming Zhang, Jianshu Chen, Dong Yu* [[paper]](https://arxiv.org/abs/2307.03987) 2023.07

## Mitigation

#### Retrieval-Augmented LLM

1. **Mitigating Language Model Hallucination with Interactive Question-Knowledge Alignment** `arXiv 2023`

   *Shuo Zhang, Liangming Pan, Junzhou Zhao, William Yang Wang* [[paper]](https://arxiv.org/abs/2305.13669) 2023.05

2. **Enabling Large Language Models to Generate Text with Citations** `arXiv 2023` 

   *Tianyu Gao, Howard Yen, Jiatong Yu, Danqi Chen* [[paper]](https://arxiv.org/abs/2305.14627) 2023.05

3. **Active Retrieval Augmented Generation** `arXiv 2023`

   *Zhengbao Jiang, Frank F. Xu, Luyu Gao, Zhiqing Sun, Qian Liu, Jane Dwivedi-Yu, Yiming Yang, Jamie Callan, Graham Neubig* [[paper]](https://arxiv.org/abs/2305.06983) 2023.06

4. **Lost in the Middle: How Language Models Use Long Contexts** `arXiv 2023`

   *Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang* [[paper]](https://arxiv.org/abs//2307.03172) 2023.07

#### Attributable LLM

1. **RARR: Researching and Revising What Language Models Say, Using Language Models** `ACL 2023`

   *Luyu Gao, Zhuyun Dai, Panupong Pasupat, Anthony Chen, Arun Tejasvi Chaganty, Yicheng Fan, Vincent Y. Zhao, Ni Lao, Hongrae Lee, Da-Cheng Juan, Kelvin Guu* [[paper]](https://arxiv.org/abs/2210.08726) 2022.10

2. **Attributed Question Answering: Evaluation and Modeling for Attributed Large Language Models** `arXiv 2022`

   *Bernd Bohnet, Vinh Q. Tran, Pat Verga, Roee Aharoni, Daniel Andor, Livio Baldini Soares, Massimiliano Ciaramita, Jacob Eisenstein, Kuzman Ganchev, Jonathan Herzig, Kai Hui, Tom Kwiatkowski, Ji Ma, Jianmo Ni, Lierni Sestorain Saralegui, Tal Schuster, William W. Cohen, Michael Collins, Dipanjan Das, Donald Metzler, Slav Petrov, Kellie Webster* [[paper]](https://arxiv.org/abs/2212.08037) 2022.12

3. **Characterizing Attribution and Fluency Tradeoffs for Retrieval-Augmented Large Language Models** `arXiv 2023`

   *Renat Aksitov, Chung-Ching Chang, David Reitter, Siamak Shakeri, Yunhsuan Sung* [[paper]](https://arxiv.org/abs/2302.05578) 2023.02

4. **Evaluating Verifiability in Generative Search Engines** `arXiv 2023`

   *Nelson F. Liu, Tianyi Zhang, Percy Liang* [[paper]](https://arxiv.org/abs/2304.09848) 2023.04

5. **Enabling Large Language Models to Generate Text with Citations** `arXiv 2023`

   *Tianyu Gao, Howard Yen, Jiatong Yu, Danqi Chen* [[paper]](https://arxiv.org/abs/2305.14627) 2023.05

6. **PURR: Efficiently Editing Language Model Hallucinations by Denoising Language Model Corruptions** `arXiv 2023`

   *Anthony Chen, Panupong Pasupat, Sameer Singh, Hongrae Lee, Kelvin Guu* [[paper]](https://arxiv.org/abs/2305.14908) 2023.05

7. **Automatic Evaluation of Attribution by Large Language Models** `arXiv 2023`

   *Xiang Yue, Boshi Wang, Kai Zhang, Ziru Chen, Yu Su, Huan Sun* [[paper]](https://arxiv.org/abs/2305.06311) 2023.05

8. **Citation: A Key to Building Responsible and Accountable Large Language Models** `arXiv 2023`

   *Jie Huang, Kevin Chen-Chuan Chang* [[paper]](https://arxiv.org/abs/2307.02185) 2023.07

#### Decoding

1. **Contrastive Decoding: Open-ended Text Generation as Optimization** `ACL 2023`

   *Xiang Lisa Li, Ari Holtzman, Daniel Fried, Percy Liang, Jason Eisner, Tatsunori Hashimoto, Luke Zettlemoyer, Mike Lewis* [[paper]](https://arxiv.org/abs/2210.15097)

2. **Look-back Decoding for Open-Ended Text Generation** `arXiv 2023`

   *Nan Xu, Chunting Zhou, Asli Celikyilmaz, Xuezhe Ma* [[paper]](https://arxiv.org/abs/2305.13477) 2023.05

3. **Trusting Your Evidence: Hallucinate Less with Context-aware Decoding** `arXiv 2023`

   *Weijia Shi, Xiaochuang Han, Mike Lewis, Yulia Tsvetkov, Luke Zettlemoyer, Scott Wen-tau Yih* [[paper]](https://arxiv.org/abs/2305.14739) 2023.05

4. **KL-Divergence Guided Temperature Sampling** `arXiv 2023`

   *Chung-Ching Chang, David Reitter, Renat Aksitov, Yun-Hsuan Sung* [[paper]](https://arxiv.org/abs/2306.01286) 2023.06

## Evaluation

1. **A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity** `arXiv 2023`

   *Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung* [[paper]](https://arxiv.org/abs/2302.04023) 2023.02

## Benchmark

1. **HaluEval: A Large-Scale Hallucination Evaluation Benchmark for Large Language Models** `arXiv 2023`

   *Junyi Li, Xiaoxue Cheng, Wayne Xin Zhao, Jian-Yun Nie, Ji-Rong Wen* [[paper]](https://arxiv.org/abs/2305.11747) 2023.05