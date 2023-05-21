---
permalink: /vacancies/
title: "Vacancies"
classes: wide
---

### <u>PhD positions</u>
There are currenly no available funded PhD positions. 

**Self or Externally Funded PhD Positions:**<br/>
If you are passionate about research and seek academic freedom, explore self-funded PhD opportunities with us. Choose your own topic, access top resources, and receive personalized mentorship. You are encouraged to submit your applications directly to me via email.

### Closed
**PhD Position in Reinforcement Learning** <small class="news-date">March 2023</small>
<br/>I am looking for a highly motivated and skilled PhD candidate to work in the area of Reinforcement Learning. For more information regarding the position and how to apply, please follow this [link](https://jobs.tue.nl/en/vacancy/phd-position-in-reinforcement-learning-990306.html). Deadline is May 7th, 2023. 

### <u>Master thesis</u>
**Efficient Unbiased Training of Large-scale Distributed RL**<br/>
In collaboration with [Ali Ramezani-Kebrya, University of Oslo](https://www.mn.uio.no/ifi/english/people/aca/ali/index.html).
<details>
  <summary>See the description</summary>
  <p>
  It is widely known that training deep neural networks on huge datasets improves learning. However, huge datasets and deep neural networks can no longer be trained on a single machine. One common solution is to train using distributed systems. In addition to traditional data-centers, in federated learning,  multiple clients, e.g., a few hospitals and thousands of cellphones learn a model without sharing local data to prevent the potential privacy issues.</p>
 <p>
Several methods have been proposed to accelerate training for classical empirical risk minimization (ERM) in supervised learning and beyond such as gradient (or model update) compression, gradient sparsification, weight quantization/sparsification, and reducing the frequency of communication though multiple local updates. Unbiased vector quantization is in particular an interesting compression method due to both enjoying strong theoretical guarantees along with providing communication efficiency  on the fly, i.e., it converges under the same hyperparameteres tuned for vanilla uncompressed SGD while providing substantial savings in terms of communication costs [1-4].
 </p>
     <p>
In this project, we investigate how to accelerate training deep neural networks in distributed reinforcement learning (DRL) [5-10]. In particular, our goal is to show: 1) How can we modify adaptive variants of unbiased quantization schemes tailored to general DRL problems; 2) Can we achieve optimal rate of convergence while establishing strong guarantees on the number of communication bits? 3) Do our new methods show strong empirical performance on deep neural networks and huge datasets, both in terms of performance measures and scalability?
<br/>
     </p>
   <p>
This project is available for a master student with a strong background in reinforcement learning. Students should be familiar with reinforcement learning, PyTorch. Familiarity with distributed optimization, MPI, and CUDA is a plus.
      </p>
<sup>
[1] Dan Alistarh, Demjan Grubic, Jerry Z. Li, Ryota Tomioka, and Milan Vojnovic. QSGD: Communication-efficient SGD via gradient quantization and encoding. In Proc. NeurIPS, 2017.<br/>

[2] Fartash Faghri, Iman Tabrizian, Ilia Markov, Dan Alistarh, Daniel M. Roy, and Ali  Ramezani-Kebrya. Adaptive gradient quantization for data-parallel SGD. In Proc. NeurIPS, 2020.<br/>

[3] Ali Ramezani-Kebrya, Fartash Faghri, Ilya Markov, Vitalii Aksenov, Dan Alistarh, and Daniel M. Roy. NUQSGD: Provably communication-efficient data-parallel SGD via nonuniform quantization. JMLR, 22(114):1–43, 2021.<br/>

[4] Ali Ramezani-Kebrya, Kimon Antonakopoulos, Igor Krawczuk, Justin Deschenaux, and Volkan Cevher, Distributed Extra-gradient with Optimal Complexity and Communication Guarantees, to appear at ICLR 2023.<br/>
[5] Drew Bagnell and Andrew Ng. On local rewards and scaling distributed reinforcement learning. In Proc. NeurIPS, 2005.<br/>

[6] Eric Liang, Richard Liaw, Robert Nishihara, Philipp Moritz, Roy Fox, Ken Goldberg, Joseph Gonzalez, Michael Jordan, Ion Stoica. RLlib: Abstractions for distributed reinforcement learning. In Proc. ICML, 2018.<br/>

[7] Xiaofeng Fan, Yining Ma, Zhongxiang Dai, Wei Jing, Cheston Tan, and Bryan Kian Hsiang Low. Fault-Tolerant Federated Reinforcement Learning with Theoretical Guarantee. In Proc. NeurIPS, 2021.<br/>

[8] Srivatsan Krishnan, Maximilian Lam, Sharad Chitlangia, Zishen Wan, Gabriel Barth-Maron, Aleksandra Faust, and Vijay Janapa Reddi. QuaRL: Quantization for sustainable reinforcement learning. arXiv:1910.01055, 2021. <br/>

[9] Srivatsan Krishnan, Maximilian Lam, Sharad Chitlangia, Zishen Wan, Gabriel Barth-Maron, Aleksandra Faust, and Vijay Janapa Reddi. Settling the communication complexity for distributed offline reinforcement learning. arXiv:1910.01055, 2022.<br/>

[10] Sajad Khodadadian, Pranay Sharma, Gauri Joshi, and Siva Theja Maguluri. Federated reinforcement learning: Linear speedup under Markovian sampling. In ICML, 2022.</sup><br/>
</details>
<br/>
**Offline RL under Distribution Shifts**<br/>
In collaboration with [Ali Ramezani-Kebrya, University of Oslo](https://www.mn.uio.no/ifi/english/people/aca/ali/index.html).
<details>
  <summary>See the description</summary>
  <p>
  Distribution shifts between a source and a target domain have been a prominent problem in machine learning for several decades [1-3]. Covariance shift (as well as its assumption) is the most commonly used and studied in theory and practice in distribution shifts [1-3]. Handling covariate shift is a challenging issue. The premise behind such shifts is that data is frequently biased, and this results in distribution shifts that can be estimated by assuming some (unlabelled) knowledge of the target distribution. Density ratio estimation is an important step in various machine learning problems such as learning under covariate shift, learning under noisy labels, anomaly detection, two-sample testing, causal inference, change-point detection, and classification from positive and unlabelled data [1-3].<br/>
  </p>
    <p>
The primary challenge in offline RL is successfully handling distributional shifts [4]. Developing efficient and accurate density ratio estimation methods to obtain a consistent estimate of the actual Q-function using data from past interactions with the environment is a major problem in RL [4-7]. <br/>  </p>
    <p>
This project is available for a master student with a strong background in reinforcement learning. Students should be familiar with PyTorch. 
<br/>  </p>
  <sub>
[1] Masashi Sugiyama, Matthias Krauledat, and Klaus-Robert Müller. Covariate shift adaptation by importance weighted cross validation. JMLR, 8(5):1-21, 2007.<br/>

[2] Takafumi Kanamori and Shohei Hido and Masashi Sugiyama. A least-squares approach to direct importance estimation. JMLR, 10:1–55, 2009.
<br/>
[3] Ali Ramezani-Kebrya, Fanghui Liu, Thomas Pethick, Grigorios Chrysos, and Volkan Cevher. Federated learning under distribution shifts with generalization guarantees. under review.<br/>

[4] https://bair.berkeley.edu/blog/2020/12/07/offline/<br/>
[5] Aviral Kumar, Aurick Zhou, George Tucker, and Sergey Levine. Conservative q-learning for offline reinforcement learning. In Proc. NeurIPS, 2020.<br/>
[6] Masatoshi Uehara, Masahiro Kato, and Shota Yasui. Off-policy evaluation and learning for external validity under a covariate shift. In Proc. NeurIPS, 2020.<br/>
[7] Ilya Kostrikov, Ashvin Nair, and Sergey Levine. Offline reinforcement learning with implicit Q-learning. In Proc. ICLR, 2022.<br/>
  </sub>
</details>

<br/>
### <u>Bachelor thesis</u>

