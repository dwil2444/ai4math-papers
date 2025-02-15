# AI for Mathematics (AI4Math) Papers

## Table of Contents

- [Survey/Position](#survey)
- [Automated Theorem Proving](#automated-theorem-proving)
- [Synthetic Theorem Generation](#synthetic-theorem-generation)
- [Autoformalization](#autoformalization)
- [Proof Refactoring](#proof-refactoring)
- [Premise Selection](#premise-selection)
- [Benchmarks](#benchmarks)
- [Human-in-the-loop](#human-in-the-loop)
- [Constructing Examples / Counterexamples](#constructing-examples--counterexamples)

## Survey

- **Formal Mathematical Reasoning: A New Frontier in AI**  *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2412.16075)]

    *Kaiyu Yang, Gabriel Poesia, Jingxuan He, Wenda Li, Kristin Lauter, Swarat Chaudhuri, Dawn Song*


---------------------------------------

## Automated Theorem Proving

- **Holophrasm: a neural Automated Theorem Prover for higher-order logic.** *arXiv preprint 2016* [[pdf](https://arxiv.org/pdf/1608.02644.pdf)]

    *Daniel Whalen*

- **Deep Network Guided Proof Search.** *21st International
Conference on Logic for Programming, Artificial Intelligence and Reasoning 2017* [[pdf](https://arxiv.org/pdf/1701.06972.pdf)]

    *Sarah Loos, Geoffrey Irving, Christian Szegedy, Cezary Kaliszyk*

- **Reinforcement Learning of Theorem Proving.** *NeurIPS 2018* [[pdf](https://arxiv.org/pdf/1805.07563.pdf)]

    *Cezary Kaliszyk, Josef Urban, Henryk Michalewski, Miroslav Olšák*

- **GamePad: A Learning Environment for Theorem Proving.** *ICLR 2019* [[pdf](https://openreview.net/pdf?id=r1xwKoR9Y7)] [[code](https://github.com/ml4tp/gamepad)]

    *Daniel Huang, Prafulla Dhariwal, Dawn Song, Ilya Sutskever*

- **HOList: An Environment for Machine Learning of Higher Order Logic Theorem Proving.** *ICML 2019* [[pdf](http://proceedings.mlr.press/v97/bansal19a/bansal19a.pdf)] [[dataset](https://sites.google.com/view/holist/home)]

    *Kshitij Bansal, Sarah Loos, Markus Rabe, Christian Szegedy, Stewart Wilcox*

- **Learning to Prove Theorems via Interacting with Proof Assistants.** *ICML 2019* [[pdf](http://proceedings.mlr.press/v97/yang19a/yang19a.pdf)] [[code](https://github.com/princeton-vl/CoqGym)]

    *Kaiyu Yang, Jia Deng*

- **Graph Representations for Higher-Order Logic and Theorem Proving.** *AAAI 2020* [[pdf](https://arxiv.org/pdf/1905.10006.pdf)]

    *Aditya Paliwal, Sarah Loos, Markus Rabe, Kshitij Bansal, Christian Szegedy*

- **Generative Language Modeling for Automated Theorem Proving.** *arXiv preprint 2020* [[pdf](https://arxiv.org/pdf/2009.03393.pdf)]
    
    *Stanislas Polu, Ilya Sutskever*

- **Learning to Prove Theorems by Learning to Generate Theorems.** *NeurIPS 2020* [[pdf](https://proceedings.neurips.cc/paper/2020/file/d2a27e83d429f0dcae6b937cf440aeb1-Paper.pdf)] [[code](https://github.com/princeton-vl/MetaGen)]

    *Mingzhe Wang, Jia Deng*


- **TacticToe: Learning to Prove with Tactics.** *Journal of Automated Reasoning 2021* [[pdf](https://arxiv.org/pdf/1804.00596.pdf)]


    *Thibault Gauthier, Cezary Kaliszyk, Josef Urban, Ramana Kumar, Michael Norrish*

- **A Deep Reinforcement Learning Approach to First-Order Logic Theorem Proving.** *AAAI 2021* [[pdf](https://arxiv.org/pdf/1911.02065.pdf)] [[code](https://github.com/IBM/TRAIL)]

    *Maxwell Crouse, Ibrahim Abdelaziz, Bassem Makni, Spencer Whitehead, Cristina Cornelio, Pavan Kapanipathi, Kavitha Srinivas, Veronika Thost, Michael Witbrock, Achille Fokoue*

- **TacticZero: Learning to Prove Theorems from Scratch with Deep Reinforcement Learning.** *NeurIPS 2021* [[pdf](https://openreview.net/pdf?id=edmYVRkYZv)]

    *Minchao Wu, Michael Norrish, Christian Walder, Amir Dezfouli*


- **Learning to Guide a Saturation-Based Theorem Prover.** *TPAMI 2022* [[pdf](https://arxiv.org/pdf/2106.03906.pdf)] [[code](https://github.com/IBM/TRAIL)]

    *Ibrahim Abdelaziz, Maxwell Crouse, Bassem Makni, Vernon Austil, Cristina Cornelio, Shajith Ikbal, Pavan Kapanipathi, Ndivhuwo Makondo, Kavitha Srinivas, Michael Witbrock, Achille Fokoue*

- **Proof Artifact Co-training for Theorem Proving with Language Model.** *ICLR 2022* [[pdf](https://openreview.net/pdf?id=rpxJc9j04U)] [[tactic step data](https://github.com/jasonrute/lean_proof_recording)] [[PACT data](https://github.com/jesse-michael-han/lean-step-public)]

    *Jesse Michael Han, Jason Rute, Yuhuai Wu, Edward W. Ayers, Stanislas Polu*

- **Formal Mathematics Statement Curriculum Learning.** *ICML 2022* [[pdf](https://arxiv.org/pdf/2202.01344.pdf)]

    *Stanislas Polu, Jesse Michael Han, Kunhao Zheng, Mantas Baksys, Igor Babuschkin, Ilya Sutskever*


- **Thor: Wielding Hammers to Integrate Language Models and Automated Theorem Provers.** *NeurIPS 2022* [[pdf](https://openreview.net/pdf?id=fUeOyt-2EOp)]

    *Albert Q. Jiang, Wenda Li, Szymon Tworkowski, Konrad Czechowski, Tomasz Odrzygóźdź, Piotr Miłoś, Yuhuai Wu, Mateja Jamnik*


- **NaturalProver: Grounded Mathematical Proof Generation with Language Models.** *NeurIPS 2022* [[pdf](https://openreview.net/pdf?id=rhdfTOiXBng)] [[code](https://github.com/wellecks/naturalprover)]

    *Sean Welleck, Jiacheng Liu, Ximing Lu, Hannaneh Hajishirzi, Yejin Choi*



- **HyperTree Proof Search for Neural Theorem Proving.** *NeurIPS 2022* [[pdf](https://openreview.net/pdf?id=J4pX8Q8cxHH)]

    *Guillaume Lample, Timothee Lacroix, Marie-anne Lachaux, Aurelien Rodriguez, Amaury Hayat, Thibaut Lavril, Gabriel Ebner, Xavier Martinet*

- **Draft, Sketch, and Prove: Guiding Formal Theorem Provers with Informal Proofs.** *ICLR 2023* [[pdf](https://openreview.net/pdf?id=SMa9EAovKMC)] [[code](https://github.com/albertqjiang/draft_sketch_prove)]

    *Albert Qiaochu Jiang, Sean Welleck, Jin Peng Zhou, Timothee Lacroix, Jiacheng Liu, Wenda Li, Mateja Jamnik, Guillaume Lample, Yuhuai Wu*

- **Baldur: Whole-Proof Generation and Repair with Large Language Models** *arxiv preprint 2023* [[pdf](https://arxiv.org/pdf/2303.04910.pdf)]

    *Emily First, Markus N. Rabe, Talia Ringer, Yuriy Brun*
    
- **Decomposing the Enigma: Subgoal-based Demonstration Learning for Formal Theorem Proving.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2305.16366.pdf)] [[code](https://github.com/HKUNLP/subgoal-theorem-prover)]

    *Xueliang Zhao, Wenda Li, Lingpeng Kong*

- **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models.** *NeurIPS 2023 Datasets and Benchmarks Track* [[pdf](https://arxiv.org/pdf/2306.15626.pdf)] [[code](https://github.com/lean-dojo)]

    *Kaiyu Yang, Aidan M. Swope, Alex Gu, Rahul Chalamala, Peiyang Song, Shixing Yu, Saad Godil, Ryan Prenger, Anima Anandkumar*

- **DT-Solver: Automated Theorem Proving with Dynamic-Tree Sampling Guided by Proof-level Value Function.** *ACL 2023* [[pdf](https://aclanthology.org/2023.acl-long.706.pdf)]

    *Haiming Wang, Ye Yuan, Zhengying Liu, Jianhao Shen, Yichun Yin, Jing Xiong, Enze Xie, Han Shi, Yujun Li, Lin Li, Jian Yin, Zhenguo Li, Xiaodan Liang*

- **Lyra: Orchestrating Dual Correction in Automated Theorem Proving.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2309.15806.pdf)] [[code](https://github.com/chuanyang-Zheng/Lyra-theorem-prover)]

    *Chuanyang Zheng, Haiming Wang, Enze Xie, Zhengying Liu, Jiankai Sun, Huajian Xin, Jianhao Shen, Zhenguo Li, Yu Li*

- **A Language-Agent Approach to Formal Theorem-Proving.** *arXiv preprint 2023* [[pdf](https://browse.arxiv.org/pdf/2310.04353.pdf)]

    *Amitayush Thakur, Yeming Wen, Swarat Chaudhuri*

- **LEGO-Prover: Neural Theorem Proving with Growing Libraries.** *ICLR 2024* [[pdf](https://arxiv.org/pdf/2310.00656.pdf)] [[code](https://github.com/wiio12/LEGO-Prover)]

    *Haiming Wang, Huajian Xin, Chuanyang Zheng, Lin Li, Zhengying Liu, Qingxing Cao, Yinya Huang, Jing Xiong, Han Shi, Enze Xie, Jian Yin, Zhenguo Li, Heng Liao, Xiaodan Liang*

- **LLMSTEP: LLM proofstep suggestions in Lean.** *The 3rd Workshop on Mathematical Reasoning and AI at NeurIPS 2023* [[pdf](https://arxiv.org/pdf/2310.18457.pdf)] [[code](https://github.com/wellecks/llmstep)]

    *Sean Welleck, Rahul Saha*

- **Temperature-scaled large language models for Lean proofstep prediction.** *The 3rd Workshop on Mathematical Reasoning and AI at NeurIPS 2023* [[pdf](https://mathai2023.github.io/papers/25.pdf)]

    *Fabian Gloeckle, Baptiste Roziere, Amaury Hayat, Gabriel Synnaeve*

- **Graph2Tac: Learning Hierarchical Representations of Math Concepts in Theorem proving.** *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2401.02949.pdf)] [[code](https://github.com/IBM/graph2tac)]

    *Jason Rute, Miroslav Olšák, Lasse Blaauwbroek, Fidel Ivan Schaposnik Massolo, Jelle Piepenbrock, Vasily Pestun*

- **Solving olympiad geometry without human demonstrations.** *Nature 2024* [[pdf](https://www.nature.com/articles/s41586-023-06747-5)][[code](https://github.com/google-deepmind/alphageometry)]

    *Trieu H. Trinh, Yuhuai Wu, Quoc V. Le, He He, Thang Luong*

- **FGeo-TP: A Language Model-Enhanced Solver for Geometry Problems.** *Symmetry 2024* [[pdf](https://arxiv.org/pdf/2402.09047)]

    *Yiming He, Jia Zou, Xiaokai Zhang, Na Zhu, Tuo Leng*

- **FGeo-HyperGNet: Geometry Problem Solving Integrating Formal Symbolic System and Hypergraph Neural Network.** *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2402.11461)][[code](https://github.com/BitSecret/HyperGNet)]

    *Xiaokai Zhang, Na Zhu, Yiming He, Jia Zou, Cheng Qin, Yang Li, Zhenbing Zeng, Tuo Leng*

- **FGeo-SSS: A Search-Based Symbolic Solver for Human-like Automated Geometric Reasoning.** *Symmetry 2024* [[pdf](https://www.mdpi.com/2073-8994/16/4/404)]

    *Xiaokai Zhang, Na Zhu, Yiming He, Jia Zou, Cheng Qin, Yang Li, Tuo Leng*

- **FGeo-DRL: Deductive Reasoning for Geometric Problems through Deep Reinforcement Learning.** *Symmetry 2024* [[pdf](https://arxiv.org/pdf/2402.09051)]

    *Jia Zou, Xiaokai Zhang, Yiming He, Na Zhu, Tuo Leng*

- **Wu's Method can Boost Symbolic AI to Rival Silver Medalists and AlphaGeometry to Outperform Gold Medalists at IMO Geometry.** *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2404.06405)][[code](https://huggingface.co/datasets/bethgelab/simplegeometry)]

    *Shiven Sinha, Ameya Prabhu, Ponnurangam Kumaraguru, Siddharth Bhat, Matthias Bethge*

- **Learn from Failure: Fine-Tuning LLMs with Trial-and-Error Data for Intuitionistic Propositional Logic Proving.** *ACL 2024* [[pdf](https://arxiv.org/pdf/2404.07382)] [[dataset](https://huggingface.co/datasets/KomeijiForce/PropL)]

    *Chenyang An, Zhibo Chen, Qihao Ye, Emily First, Letian Peng, Jiayun Zhang, Zihan Wang, Sorin Lerner, Jingbo Shang*

- **Proving Theorems Recursively.** *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2405.14414)] [[code](https://github.com/wiio12/POETRY)]

    *Haiming Wang, Huajian Xin, Zhengying Liu, Wenda Li, Yinya Huang, Jianqiao Lu, Zhicheng Yang, Jing Tang, Jian Yin, Zhenguo Li, Xiaodan Liang*

- **DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data.** *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2405.14333)]

    *Huajian Xin, Daya Guo, Zhihong Shao, Zhizhou Ren, Qihao Zhu, Bo Liu, Chong Ruan, Wenda Li, Xiaodan Liang*

- **DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search.** *arXiv preprint 2024* [[pdf](https://www.arxiv.org/pdf/2408.08152)] [[code](https://github.com/deepseek-ai/DeepSeek-Prover-V1.5)]

    *Huajian Xin, Z.Z. Ren, Junxiao Song, Zhihong Shao, Wanjia Zhao, Haocheng Wang, Bo Liu, Liyue Zhang, Xuan Lu, Qiushi Du, Wenjun Gao, Qihao Zhu, Dejian Yang, Zhibin Gou, Z.F. Wu, Fuli Luo, Chong Ruan*

---------------------------------------

## Synthetic Theorem Generation

- **Learning to Prove Theorems by Learning to Generate Theorems.** *NeurIPS 2020* [[pdf](https://proceedings.neurips.cc/paper/2020/file/d2a27e83d429f0dcae6b937cf440aeb1-Paper.pdf)] [[code](https://github.com/princeton-vl/MetaGen)]

    *Mingzhe Wang, Jia Deng*

- **INT: An Inequality Benchmark for Evaluating Generalization in Theorem Proving.** *ICLR 2021* [[pdf](https://openreview.net/pdf?id=O6LPudowNQm)] [[code](https://github.com/albertqjiang/INT)]

    *Yuhuai Wu, Albert Q. Jiang, Jimmy Ba, Roger Grosse*

- **Solving olympiad geometry without human demonstrations.** *Nature 2024* [[pdf](https://www.nature.com/articles/s41586-023-06747-5)][[code](https://github.com/google-deepmind/alphageometry)]

    *Trieu H. Trinh, Yuhuai Wu, Quoc V. Le, He He, Thang Luong*

- **MUSTARD: Mastering Uniform Synthesis of Theorem and Proof Data.** *ICLR 2024* [[pdf](https://openreview.net/pdf?id=8xliOUg9EW)][[code](https://github.com/Eleanor-H/MUSTARD)]

    *Yinya Huang, Xiaohan Lin, Zhengying Liu, Qingxing Cao, Huajian Xin, Haiming Wang, Zhenguo Li, Linqi Song, Xiaodan Liang*


- **ATG: Benchmarking Automated Theorem Generation for Generative Language Models.** *NAACL 2024* [[pdf](https://openreview.net/forum?id=H0RzzhAxTv)]

    *Xiaohan Lin, Qingxing Cao, Yinya Huang, Zhicheng Yang, Zhengying Liu, Zhenguo Li, Xiaodan Liang*


---------------------------------------


## Autoformalization


- **Exploration of Neural Machine Translation in Autoformalization of Mathematics in Mizar.** *CPP 2020* [[pdf](https://arxiv.org/pdf/1912.02636.pdf)]

    *Qingxiang Wang, Chad Brown, Cezary Kaliszyk, Josef Urban*

- **Autoformalization with Large Language Models.** *NeurIPS 2022* [[pdf](https://openreview.net/pdf?id=IUikebJ1Bf0)]
    
    *Yuhuai Wu, Albert Qiaochu Jiang, Wenda Li, Markus Norman Rabe, Charles E Staats, Mateja Jamnik, Christian Szegedy*



- **ProofNet: Autoformalizing and Formally Proving Undergraduate-Level Mathematics.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2302.12433.pdf)] [[code](https://github.com/zhangir-azerbayev/proofnet)]

    *Zhangir Azerbayev, Bartosz Piotrowski, Hailey Schoelkopf, Edward W. Ayers, Dragomir Radev, Jeremy Avigad*

- **Multilingual Mathematical Autoformalization.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2311.03755.pdf)] [[code](https://github.com/albertqjiang/MMA)]

    *Albert Q. Jiang, Wenda Li, Mateja Jamnik*

- **Lean Workbook: A large-scale Lean problem set formalized from natural language math problems.** *arXiv preprint 2024* [[pdf](https://arxiv.org/pdf/2406.03847)] [[dataset](https://huggingface.co/datasets/internlm/Lean-Workbook)] [[code](https://github.com/InternLM/InternLM-Math)]

    *Huaiyuan Ying, Zijian Wu, Yihan Geng, Jiayu Wang, Dahua Lin, Kai Chen*

- **TheoremLlama: Transforming General-Purpose LLMs into Lean4 Experts.** *EMNLP 2024* [[pdf](https://arxiv.org/pdf/2407.03203)] [[code](https://github.com/RickySkywalker/TheoremLlama)]

    *Ruida Wang, Jipeng Zhang, Yizhen Jia, Rui Pan, Shizhe Diao, Renjie Pi, Tong Zhang*

---------------------------------------


## Proof Refactoring


- **REFACTOR: Learning to Extract Theorems from Proofs.** *ICLR 2024* [[pdf](https://arxiv.org/pdf/2402.17032.pdf)] [[code](https://github.com/jinpz/refactor)]

    *Jin Peng Zhou, Yuhuai Wu, Qiyang Li, Roger Grosse*


---------------------------------------

## Premise Selection


- **DeepMath - Deep Sequence Models for Premise Selection.** *NeurIPS 2016* [[pdf](https://proceedings.neurips.cc/paper/2016/file/f197002b9a0853eca5e046d9ca4663d5-Paper.pdf)]

    *Alex A. Alemi, Francois Chollet, Niklas Een, Geoffrey Irving, Christian Szegedy, Josef Urban*

- **Premise Selection for Theorem Proving by Deep Graph Embedding.** *NeurIPS 2017* [[pdf](https://proceedings.neurips.cc/paper_files/paper/2017/file/18d10dc6e666eab6de9215ae5b3d54df-Paper.pdf)]

    *Mingzhe Wang, Yihe Tang, Jian Wang, Jia Deng*

- **Natural Language Premise Selection: Finding Supporting Statements for Mathematical Text.** *LREC 2020* [[pdf](https://aclanthology.org/2020.lrec-1.266.pdf)] [[code](https://github.com/debymf/nl-ps)]

    *Deborah Ferreira, André Freitas*

- **Premise Selection in Natural Language Mathematical Texts.** *ACL 2020* [[pdf](https://aclanthology.org/2020.acl-main.657.pdf)]

    *Deborah Ferreira, André Freitas*

- **Machine-Learned Premise Selection for Lean** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2304.00994.pdf)] [[code](https://github.com/BartoszPiotrowski/lean-premise-selection)]

    *Bartosz Piotrowski, Ramon Fernández Mir, Edward Ayers*

- **Magnushammer: A Transformer-based Approach to Premise Selection.** *ICLR 2024* [[pdf](https://arxiv.org/pdf/2303.04488.pdf)]

    *Maciej Mikuła, Szymon Antoniak, Szymon Tworkowski, Albert Qiaochu Jiang, Jin Peng Zhou, Christian Szegedy, Łukasz Kuciński, Piotr Miłoś, Yuhuai Wu*

---------------------------------------


## Benchmarks


- **HolStep: A Machine Learning Dataset for Higher-order Logic Theorem Proving.** *ICLR 2017* [[pdf](https://openreview.net/pdf?id=ryuxYmvel)] [[dataset](http://cl-informatik.uibk.ac.at/cek/holstep/)] [[code](https://github.com/tensorflow/deepmath/tree/master/deepmath/holstep_baselines)]

    *Cezary Kaliszyk, François Chollet, Christian Szegedy*

- **Learning to Prove Theorems via Interacting with Proof Assistants.** *ICML 2019* [[pdf](http://proceedings.mlr.press/v97/yang19a/yang19a.pdf)] [[code](https://github.com/princeton-vl/CoqGym)]

    *Kaiyu Yang, Jia Deng*


- **HOList: An Environment for Machine Learning of Higher Order Logic Theorem Proving.** *ICML 2019* [[pdf](http://proceedings.mlr.press/v97/bansal19a/bansal19a.pdf)] [[dataset](https://sites.google.com/view/holist/home)]

    *Kshitij Bansal, Sarah Loos, Markus Rabe, Christian Szegedy, Stewart Wilcox*

- **IsarStep: a Benchmark for High-level Mathematical Reasoning.** *ICLR 2021* [[pdf](https://openreview.net/pdf?id=Pzj6fzU6wkj)] [[code](https://github.com/Wenda302/IsarStep)]

    *Wenda Li, Lei Yu, Yuhuai Wu, Lawrence C. Paulson*

- **INT: An Inequality Benchmark for Evaluating Generalization in Theorem Proving.** *ICLR 2021* [[pdf](https://openreview.net/pdf?id=O6LPudowNQm)] [[code](https://github.com/albertqjiang/INT)]

    *Yuhuai Wu, Albert Q. Jiang, Jimmy Ba, Roger Grosse*

- **NaturalProofs: Mathematical Theorem Proving in Natural Language.** *NeurIPS 2021 Datasets and Benchmarks Track (Round 1)* [[pdf](https://openreview.net/pdf?id=Jvxa8adr3iY)] [[code](https://github.com/wellecks/naturalproofs)]

    *Sean Welleck, Jiacheng Liu, Ronan Le Bras, Hannaneh Hajishirzi, Yejin Choi, Kyunghyun Cho*

- **MiniF2F: a cross-system benchmark for formal Olympiad-level mathematics.** *ICLR 2022* [[pdf](https://openreview.net/pdf?id=9ZPegFuFTFv)] [[dataset](https://github.com/openai/miniF2F)]
    
    *Kunhao Zheng, Jesse Michael Han, Stanislas Polu*

- **ProofNet: Autoformalizing and Formally Proving Undergraduate-Level Mathematics.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2302.12433.pdf)] [[code](https://github.com/zhangir-azerbayev/proofnet)]

    *Zhangir Azerbayev, Bartosz Piotrowski, Hailey Schoelkopf, Edward W. Ayers, Dragomir Radev, Jeremy Avigad*

- **Evaluating Language Models for Mathematics through Interactions.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2306.01694.pdf)] [[code](https://github.com/collinskatie/checkmate/tree/main)]

    *Katherine M. Collins, Albert Q. Jiang, Simon Frieder, Lionel Wong, Miri Zilka, Umang Bhatt, Thomas Lukasiewicz, Yuhuai Wu, Joshua B. Tenenbaum, William Hart, Timothy Gowers, Wenda Li, Adrian Weller, Mateja Jamnik*

- **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models.** *NeurIPS 2023 Datasets and Benchmarks Track* [[pdf](https://arxiv.org/pdf/2306.15626.pdf)] [[code](https://github.com/lean-dojo)]

    *Kaiyu Yang, Aidan M. Swope, Alex Gu, Rahul Chalamala, Peiyang Song, Shixing Yu, Saad Godil, Ryan Prenger, Anima Anandkumar*

- **FIMO: A Challenge Formal Dataset for Automated Theorem Proving.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2309.04295.pdf)]

    *Chengwu Liu, Jianhao Shen, Huajian Xin, Zhengying Liu, Ye Yuan, Haiming Wang, Wei Ju, Chuanyang Zheng, Yichun Yin, Lin Li, Ming Zhang, Qun Liu*

- **TRIGO: Benchmarking Formal Mathematical Proof Reduction for Generative Language Models.** *EMNLP 2023* [[pdf](https://arxiv.org/pdf/2310.10180.pdf)] [[code](https://github.com/menik1126/TRIGO)]

    *Jing Xiong, Jianhao Shen, Ye Yuan, Haiming Wang, Yichun Yin, Zhengying Liu, Lin Li, Zhijiang Guo, Qingxing Cao, Yinya Huang, Chuanyang Zheng, Xiaodan Liang, Ming Zhang, Qun Liu*

- **MLFMF: Data Sets for Machine Learning for Mathematical Formalization.** *NeurIPS 2023* [[pdf](https://arxiv.org/pdf/2310.16005.pdf)] [[code](https://github.com/ul-fmf/mlfmf-data)]
        
    *Andrej Bauer, Matej Petković, Ljupčo Todorovski*

- **FormalGeo: The First Step Toward Human-like IMO-level Geometric Automated Reasoning.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2310.18021.pdf)] [[code](https://github.com/BitSecret/FormalGeo)]

    *Xiaokai Zhang, Na Zhu, Yiming He, Jia Zou, Qike Huang, Xiaoxiao Jin, Yanjun Guo, Chenyang Mao, Zhe Zhu, Dengfeng Yue, Fangzhen Zhu, Yang Li, Yifan Wang, Yiwen Huang, Runan Wang, Cheng Qin, Zhenbing Zeng, Shaorong Xie, Xiangfeng Luo, Tuo Leng*

- **MUSTARD: Mastering Uniform Synthesis of Theorem and Proof Data.** *ICLR 2024* [[pdf](https://openreview.net/pdf?id=8xliOUg9EW)][[code](https://github.com/Eleanor-H/MUSTARD)]

    *Yinya Huang, Xiaohan Lin, Zhengying Liu, Qingxing Cao, Huajian Xin, Haiming Wang, Zhenguo Li, Linqi Song, Xiaodan Liang*

- **ATG: Benchmarking Automated Theorem Generation for Generative Language Models.** *NAACL 2024* [[pdf](https://openreview.net/forum?id=H0RzzhAxTv)]

    *Xiaohan Lin, Qingxing Cao, Yinya Huang, Zhicheng Yang, Zhengying Liu, Zhenguo Li, Xiaodan Liang*


---------------------------------------

## Human-in-the-loop
- **Advancing mathematics by guiding human intuition with AI.** *Nature 2021* [[pdf](https://www.nature.com/articles/s41586-021-04086-x)]
    
    *Alex Davies, Petar Veličković, Lars Buesing, Sam Blackwell, Daniel Zheng, Nenad Tomašev, Richard Tanburn, Peter Battaglia, Charles Blundell, András Juhász, Marc Lackenby, Geordie Williamson, Demis Hassabis & Pushmeet Kohli*


- **Machine Learning Kreuzer--Skarke Calabi--Yau Threefolds.** *arXiv preprint 2021* [[pdf](https://arxiv.org/pdf/2112.09117.pdf)]

    *Per Berglund, Ben Campbell, Vishnu Jejjala*

- **Machine Learning Calabi-Yau Hypersurfaces.** *Physical Review D 2022* [[pdf](https://arxiv.org/pdf/2112.06350.pdf)]

    *David S. Berman, Yang-Hui He, Edward Hirst*

- **Machine learning assisted exploration for affine Deligne-Lusztig varieties.** *Peking Mathematical Journal 2024* [[pdf](https://arxiv.org/pdf/2308.11355.pdf)] [[code](https://github.com/Jinpf314/ML4ADLV/)]

    *Bin Dong, Xuhua He, Pengfei Jin, Felix Schremmer, Qingchao Yu*

- **Can Transformers Do Enumerative Geometry?** *arXiv preprint 2024* [[pdf](https://www.arxiv.org/pdf/2408.14915)]

    *Baran Hashemi, Roderic G. Corominas, Alessandro Giacchetto*

- **Deductive Verification of Chain-of-Thought Reasoning** *NeurIPS 2023* [[pdf](https://arxiv.org/pdf/2412.16075)] [[code](https://github.com/lz1oceani/verify_cot)]

    *Zhan Ling, Yunhao Fang, Xuanlin Li, Zhiao Huang, Mingu Lee, Roland Memisevic, Hao Su*

---------------------------------------

## Constructing Examples / Counterexamples

- **Constructions in combinatorics via neural networks.** *arXiv preprint 2021* [[pdf](https://arxiv.org/pdf/2104.14516.pdf)]

    *Adam Zsolt Wagner*

- **Searching for ribbons with machine learning.** *arXiv preprint 2023* [[pdf](https://arxiv.org/pdf/2304.09304.pdf)]

    *Sergei Gukov, James Halverson, Ciprian Manolescu, Fabian Ruehle*

- **Mathematical discoveries from program search with large language models.** *Nature 2024* [[pdf](https://www.nature.com/articles/s41586-023-06924-6)][[code](https://github.com/google-deepmind/funsearch)]

    *Bernardino Romera-Paredes, Mohammadamin Barekatain, Alexander Novikov, Matej Balog, M. Pawan Kumar, Emilien Dupont, Francisco J. R. Ruiz, Jordan S. Ellenberg, Pengming Wang, Omar Fawzi, Pushmeet Kohli, Alhussein Fawzi*
