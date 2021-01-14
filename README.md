# Awesome-Recommendation-and-Ranking-Systems
Maintained by Yang Gao (ustcgaoy01@gmail.com). Last Update: 12/13/2020.

Recent advances in recommendation and ranking systems. We only focus on papers published in top conferences including RecSys, WWW, SIGIR, and KDD.

## Table of Contents
* [Survey](#survey)
  * [Self-Supervised](#Survey_Self-Supervised)
  * [Ranking and Retrieval](#Survey_Rank_Retrieval)
  * [Knowledge Graph and Side Information](#Survey_KG_SideInfo)
  * [Bias Correction, Fairness and Quality](#Survey_Bias_Correction)
  * [Interpretability](#Survey_Interpretability)
  * [Feature Engineering](#Survey_FE)
  * [Personalization](#Survey_Personalization)
  * [Others](#Survey_Others)
* [Industry Papers](#industry-papers)
  * [Scalability](#Industry_Scalability)
  * [Exploit and Explore](#Industry_EE)
  * [Ranking and Retrieval](#Industry_Ranking_Retrieval)
  * [Personalization](#Industry_Personalization)
  * [Multi-Modal](#Industry_MultiModal)
  * [Interpretability](#Industry_Interpretability)
  * [Cold Start](#Industry_ColdStart)
  * [Imbalance and Limited Labels](#Industry_Imbalance)
  * [Bias Correction, Fairness, and Quality](#Industry_Bias_Correction)
  * [Privacy](#Industry_Privacy)
  * [Knowledge Graph and Side Information](#Industry_KG_SI)
  * [Transfer Learning and Multi-Task Learning](#Industry_Transfer)
  * [Feature Engineering](#Industry_FE)
  * [Computational Ads](#Industry_CompAds)
  * [Travel and Delivery](#Industry_Travel)
  * [Others](#Industry_Others)
    * [Theory](#Industry_Other_Theory)
    * [Fashion Recommendation](#Industry_Other_Fashion)
    * [E-Commerce](#Industry_Other_e-commerce)
* [Academic Papers](#academic-papers)
  * [Scalability](#Academic_Scalability)
  * [Exploit and Explore](#Academic_EE)
  * [Privacy](#Academic_Privacy)
  * [Transfer Learning and MultiTask Learning](#Academic_Transfer)
  * [Others](#Academic_Others)
* [Special Topics](#special-topics)
  * [Transformers in Recommendation/Ranking System](#transformers-in-recommendation-and-ranking-system)

<h3> Keywords </h3>
<h4> Problem </h4>

__`sca.`__: scalability &emsp; | &emsp; __`ee.`__: exploit and explore &emsp; | &emsp; __`ret.`__: retrieval &emsp; | &emsp; __`ran.`__: ranking    
__`per.`__: personalization &emsp; | &emsp; __`seq.`__: sequential info &emsp; | &emsp; __`int.`__: interpretability &emsp; | &emsp; __`cs.`__: cold start     
__`imb.`__: imbalance &emsp; | &emsp; __`bia.`__: bias correction, fairness, and quality &emsp; | &emsp; __`pri.`__: privacy    
__`kg.`__: knowledge graph and side information &emsp; | &emsp; __`tra.`__: transfer learning &emsp; | &emsp; __`mt.`__ multi-task    
__`fe.`__: feature engineering &emsp; | &emsp; __`ads.`__: computational ads &emsp; | &emsp; __`geo.`__: travel and delivery    
__`the`__: theory &emsp; | &emsp; __`fas.`__: fashion &emsp; | &emsp; __`eco.`__: e-commerce    

<h4> Architecture </h4>

__`mlp.`__: MLP &emsp; | &emsp; __`ae.`__: auto-encoder &emsp; | &emsp; __`cnn.`__: cnn &emsp; | &emsp; __`rnn.`__: rnn &emsp; | &emsp; __`rbm.`__: rbm &emsp; | &emsp; __`nad.`__: nade     
__`att.`__: neural attention &emsp; | &emsp; __`adv.`__: adversarial learning &emsp; | &emsp; __`gnn.`__: gnn &emsp; | &emsp; __`drl.`__: DRL &emsp; | &emsp; __`hyb.`__: hybrid    

<h4> Modality </h4>

__`txt.`__: text &emsp; | &emsp; __`img.`__: image &emsp; | &emsp; __`aud.`__: audio &emsp; | &emsp; __`vid.`__: video &emsp; | &emsp; __`net.`__: network&emsp; __`mm.`__: multimodal    

Statistics: :fire: stars >= 150 &emsp;|&emsp; :star: citation >= 50


## Survey
<a name="Survey_Self-Supervised"></a>
### Self-Supervised 
[A Survey on Self-supervised Pre-training for Sequential Transfer Learning in Neural Networks](https://arxiv.org/pdf/2007.00800.pdf), 2020.

[A SURVEY ON CONTRASTIVE SELF-SUPERVISED LEARNING](https://arxiv.org/pdf/2011.00362.pdf), 2020.

[Deep Metric Learning: A survey](https://www.mdpi.com/2073-8994/11/9/1066/pdf), 2019.

[Self-supervised Visual Feature Learning with Deep Neural Networks: A Survey](https://arxiv.org/pdf/1902.06162.pdf), 2019.

<a name="Survey_Rank_Retrieval"></a>
### Ranking and Retrieval

<a name="Survey_KG_SideInfo"></a>
### Knowledge Graph or Side Information
[A Survey on Knowledge Graph-Based Recommender Systems](https://arxiv.org/pdf/2003.00911.pdf), 2020.

[Research Commentary on Recommendations with Side Information: A Survey and Research Directions](https://arxiv.org/pdf/1909.12807.pdf), 2019.

[Attribute-Aware Recommender System Based on Collaborative Filtering: Survey and Classification](https://www.frontiersin.org/articles/10.3389/fdata.2019.00049/pdf), 2019.

<a name="Survey_Bias_Correction"></a>
### Bias Correction or Fairness
[Bias and Debias in Recommender System: A Survey and Future Directions](https://arxiv.org/pdf/2010.03240.pdf), 2020.

<a name="Survey_Interpretability"></a>
### Interpretability
[Explainable Recommendation: A Survey and New Perspectives](https://arxiv.org/pdf/1804.11192.pdf), 2020.

<a name="Survey_FE"></a>
### Feature Engineering
[Recommendation System Based on Heterogeneous Feature: A Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9197624), 2020.

<a name="Survey_Personalization"></a>
### Personalization
[A survey on news recommender system - Dealing with timeliness, dynamic user interest and content quality, and effects of recommendation on news readers.](https://arxiv.org/pdf/2009.04964.pdf), 2020.

[A Survey on Personalized News Recommendation Technology](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8854070), 2020.

[User Preferences in Recommendation Algorithms - The influence of user diversity, trust, and product category on privacy perceptions in recommender](https://dl.acm.org/doi/pdf/10.1145/3240323.3240393), 2018.

<a name="Survey_Others"></a>
### Others
[How Well Do People Report Time Spent on Facebook? An Evaluation of Established Survey Questions with Recommendations](https://dl.acm.org/doi/pdf/10.1145/3313831.3376435), 2020.

[Microsoft Recommenders: Best Practices for Production-Ready Recommendation Systems](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3382692), WWW, 2020.

[Microsoft Recommenders](https://dl.acm.org/doi/10.1145/3298689.3346967), Microsoft, RecSys, 2019.

[Are We Evaluating Rigorously? Benchmarking Recommendation for Reproducible Evaluation and Fair Comparison](https://dl.acm.org/doi/pdf/10.1145/3383313.3412489), RecSys, 2020.

[Neural Collaborative Filtering vs. Matrix Factorization Revisited](https://dl.acm.org/doi/pdf/10.1145/3383313.3412488), Google Research, RecSys, 2020.

[How good your recommender system is? A survey on evaluations in recommendation](https://link.springer.com/content/pdf/10.1007/s13042-017-0762-9.pdf), 2019.

[A Survey of Matrix Completion Methods for Recommendation Systems](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8400447), 2020.

[Recommender Systems for the Internet of Things: A Survey](https://arxiv.org/pdf/2007.06758.pdf), 2020.

[A Survey on Session-based Recommender Systems](https://arxiv.org/pdf/1902.04864.pdf), 2019.

[Tour recommendation and trip planning using location-based social media: a survey](https://link.springer.com/content/pdf/10.1007/s10115-018-1297-4.pdf), 2019.

[Deep Learning based Recommender System: A Survey and New Perspectives](https://dl.acm.org/doi/pdf/10.1145/3285029). 2019.

[150 Successful Machine Learning Models: 6 Lessons Learned at Booking.com](https://dl.acm.org/doi/pdf/10.1145/3292500.3330744), Booking.com, KDD, 2019.

[Sequence-Aware Recommender Systems](https://arxiv.org/pdf/1802.08452.pdf), 2018. - [Slides](https://www.slideshare.net/MassimoQuadrana/tutorial-on-sequence-aware-recommender-systems-acm-recsys-2018), [Code](https://github.com/mquad/sars_tutorial/)

[A Survey of Recommender Systems Based on Deep Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8529185), 2018.

## Industry Papers
### 2020
[[Google](https://arxiv.org/pdf/2002.08530.pdf)] Learning Multi-granular Quantized Embeddings for Large-Vocab Categorical Features in Recommender Systems [__`mlp.`__, __`sca.`__] 

[[MSRA](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380151)] LightRec: A Memory and Search-Efficient Recommender System [__`mlp.`__, __`sca.`__] 

[[Alibaba](https://arxiv.org/pdf/2003.01917.pdf)] Learning to Hash with Graph Neural Networks for Recommender Systems [__`gnn`__, __`sca.`__, __`ret.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403342)] Large-Scale Training System for 100-Million Classification at Alibaba [__`sca.`__]

[[Taobao](https://dl.acm.org/doi/pdf/10.1145/3394486.3403309)] Privileged Features Distillation at Taobao Recommendations [ __`ads.`__, __`eco.`__,__`tra.`__]

[[Google Research](https://dl.acm.org/doi/pdf/10.1145/3394486.3403296)] Scaling Graph Neural Networks with Approximate PageRank [__`sca.`__,__`ran.`__,__`gnn.`__]

[[Twitter](https://dl.acm.org/doi/pdf/10.1145/3383313.3418486)] Tuning Word2vec for Large Scale Recommendation Systems [__`mlp`__, __`sca.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3394486.3403344)] Controllable Multi-Interest Framework for Recommendation [__`mlp`__,__`seq.`__,__`ee.`__]

[[Airbnb](https://dl.acm.org/doi/pdf/10.1145/3394486.3403345)] Managing Diversity in Airbnb Search [__`hyb.`__,__`ran.`__,__`ee.`__,__`eco.`__]

[[IKEA](https://dl.acm.org/doi/pdf/10.1145/3383313.3411550)] Balancing relevance and discovery to inspire customers in the IKEA App [__`ee.`__]

[[Bloomberg](https://arxiv.org/pdf/1912.00508.pdf)] Cascading Hybrid Bandits: Online Learning to Rank for Relevance and Diversity [__`drl.`__,__`ee.`__,__`ran.`__]

[[Spotify Research](https://dl.acm.org/doi/pdf/10.1145/3383313.3418482)] Investigating Listeners’ Responses to Divergent Recommendations [__`ee.`__]

[[Facebook](https://dl.acm.org/doi/pdf/10.1145/3394486.3403305)] Embedding-based Retrieval in Facebook Search [__`ran.`__, __`ret.`__, __`txt.`__]


### 2019
[[Apple](http://ceur-ws.org/Vol-2431/paper10.pdf)] PQ-VAE: Efficient Recommendation Using Quantized Embeddings [__`mlp`__, __`sca.`__]

[[NAVER Corp.](https://arxiv.org/pdf/1908.02569.pdf)] Tripartite Heterogeneous Graph Propagation for Large-scale Social Recommendation [__`gnn`__,__`att.`__,__`sca.`__, __`ads.`__]

[[Facebook & Amazon](https://dl.acm.org/doi/pdf/10.1145/3298689.3347027) LORE: A Large-Scale Offer Recommendation Engine with Eligibility and Capacity Constraints [__`sca.`__]

[[Tecent](https://dl.acm.org/doi/pdf/10.1145/3292500.3330728)] Large-scale User Visits Understanding and Forecasting with Deep Spatial-Temporal Tensor Factorization Framework [__`hyb.`__, __`seq.`__, __`geo.`__,__`ads.`__,__`sca.`__]

[[Google](https://dl.acm.org/doi/pdf/10.1145/3292500.3330677)] TF-Ranking: Scalable TensorFlow Library for Learning-to-Rank [__`sca.`__,__`ran.`__] :star:

[[eBay and Microsoft Research](https://dl.acm.org/doi/pdf/10.1145/3298689.3347044)] When Actions Speak Louder than Clicks: A Combined Model of Purchase Probability and Long-term Customer Satisfaction [__`ee.`__, __`eco.`__]

[[Alibaba](https://dl.acm.org/doi/pdf/10.1145/3308558.3313469?casa_token=Ljqto7-qUnUAAAAA:hKMUsSiva812p5WMBkDJc3lzjsQwcY9pNiP0oWf_aVnMpaVnTeY4EOjHRu-S0cJeaIlqL1VBUKA)] How Serendipity Improves User Satisfaction with Recommendations? A Large-Scale User Evaluation [__`ee.`__]

### 2018
[[Microsoft Research](https://arxiv.org/pdf/1803.05170.pdf)] xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems [__`mlp.`__] :fire:

### 2017
[[Microsoft Research](https://www.microsoft.com/en-us/research/uploads/prod/2019/07/pp004-lian.pdf)] CCCFNet: A Content-Boosted Collaborative Filtering Neural Network for Cross Domain Recommender Systems [__`mlp.`__, __`tra.`__]

[[HuaWei](https://arxiv.org/pdf/1703.04247.pdf)] DeepFM: A Factorization-Machine based Neural Network for CTR Prediction [__`mlp.`__,__`ads.`__] :fire:

### 2016
[[Google](https://arxiv.org/pdf/1606.07792.pdf)] Wide & Deep Learning for Recommender Systems [__`mlp.`__] :fire:

<a name="Industry_Ranking_Retrieval"></a>
### Ranking and Retrieval
[Improving Deep Learning For Airbnb Search](https://dl.acm.org/doi/pdf/10.1145/3394486.3403333), Airbnb, KDD, 2020.

[Learning to Generate Personalized Query Auto-Completions via a Multi-View Multi-Task Attentive Approach](https://dl.acm.org/doi/pdf/10.1145/3394486.3403350), Alibaba, KDD, 2020.

[Managing Diversity in Airbnb Search](https://dl.acm.org/doi/pdf/10.1145/3394486.3403345), Airbnb, KDD, 2020.

[Meta-Learning for Query Conceptualization at Web Scale](https://dl.acm.org/doi/pdf/10.1145/3394486.3403357), Tecent, KDD, 2020.

[Neural Input Search for Large Scale Recommendation Models](https://dl.acm.org/doi/pdf/10.1145/3394486.3403288), Google, KDD, 2020.

[Personalized Image Retrieval with Sparse Graph Representation Learning](https://dl.acm.org/doi/pdf/10.1145/3394486.3403324), Adobe, KDD, 2020.

[Shop The Look: Building a Large Scale Visual Shopping System at Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403372), Pinterest, Inc., KDD, 2020.

[Behavior-based Popularity Ranking on Amazon Video](https://assets.amazon.science/46/06/1f9ca3fc409481ecf3522dda7e3d/behavior-based-popularity-ranking-on-amazon-video.pdf), Amazon, RecSys, 2020. - [Video](https://vimeo.com/455639105)

[Doubly Robust Estimator for Ranking Metrics with Post-Click Conversions](https://dl.acm.org/doi/pdf/10.1145/3383313.3412262), Tokyo Institute of Technology, RecSys, 2020. - [Video](https://vimeo.com/455947055)

[Users in the Loop: A Psychologically-Informed Approach to Similar Item Retrieval](https://dl.acm.org/doi/pdf/10.1145/3298689.3347047), TrueFit, RecSys, 2019.

[Click Feedback-Aware Query Recommendation Using Adversarial Examples](https://dl.acm.org/doi/pdf/10.1145/3308558.3313412), Yahoo Research, WWW, 2019.

[A Deep Generative Approach to Search Extrapolation and Recommendation](https://dl.acm.org/doi/pdf/10.1145/3292500.3330786), Tecent, KDD, 2019.

[Applying Deep Learning To Airbnb Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330658), Airbnb, KDD, 2019.

[Combining Decision Trees and Neural Networks for Learning-to-Rank in Personal Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330676), Google, KDD, 2019.

[Semantic Product Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330759), Amazon, KDD, 2019.

[Gmail Smart Compose: Real-Time Assisted Writing](https://dl.acm.org/doi/pdf/10.1145/3292500.3330723), Google, KDD, 2019.

[Personalized Attraction Enhanced Sponsored Search with Multi-task Learning](https://dl.acm.org/doi/pdf/10.1145/3292500.3330659), Alibaba, KDD, 2019.

[Seeker: Real-Time Interactive Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330733), Amazon, KDD, 2019.

<a name="Industry_Personalization"></a>
### Personalization
[Personalized Image Retrieval with Sparse Graph Representation Learning](https://dl.acm.org/doi/pdf/10.1145/3394486.3403324), Adobe, KDD, 2020.

[Personalized Prefix Embedding for POI Auto-Completion in the Search Engine of Baidu Maps](https://dl.acm.org/doi/pdf/10.1145/3394486.3403318), Baidu, KDD, 2020.

[Developing Recommendation System to provide a Personalized Learning experience at Chegg](https://dl.acm.org/doi/pdf/10.1145/3383313.3411557), Chegg, RecSys, 2020. - [Video](https://vimeo.com/455639337)

[Query as Context for Item-to-Item Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3411480), Etsy, RecSys, 2020. - [Video](https://vimeo.com/455640122)

[Contextual and Sequential User Embeddings for Large-Scale Music Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3412248), Spotify, RecSys, 2020. - [Video](https://vimeo.com/455951321)

[Contextual User Browsing Bandits for Large-Scale Online Mobile Recommendation](https://arxiv.org/pdf/2008.09368.pdf), Alibaba, RecSys, 2020. - [Video](https://vimeo.com/455949873)

[Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations](https://dl.acm.org/doi/pdf/10.1145/3383313.3412236), Tecent, RecSys, 2020. - [Video](https://vimeo.com/455952512)

[PURS: Personalized Unexpected Recommender System for Improving User Satisfaction](https://dl.acm.org/doi/pdf/10.1145/3383313.3412238), Alibaba, RecSys, 2020. - [Video](https://vimeo.com/455951792)

[Towards Multi-Language Recipe Personalisation and Recommendation](https://arxiv.org/pdf/2007.13440.pdf), CookPad, RecSys, 2020.

[Combining Context Features in Sequence-Aware Recommender Systems](http://ceur-ws.org/Vol-2431/paper3.pdf), Booking.com, RecSys, 2019.

[Context-Regularized Neural Collaborative Filtering for Game App Recommendation](http://ceur-ws.org/Vol-2431/paper4.pdf), RIKEN AIP, RecSys, 2019.

[Personalized Re-ranking for Recommendation](https://dl.acm.org/doi/pdf/10.1145/3298689.3347000), Alibaba, RecSys, 2019.

[Personalized Bundle List Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313568), Alibaba, WWW, 2019.

[Pcard: Personalized Restaurants Recommendation from Card Payment Transaction Records](https://dl.acm.org/doi/pdf/10.1145/3308558.3313494), VISA Research, WWW, 2019.

[User-Video Co-Attention Network for Personalized Micro-video Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313513), Amazon Alexa & Facebook, WWW, 2019.

[A User-Centered Concept Mining System for Query and Document Understanding at Tencent](https://dl.acm.org/doi/pdf/10.1145/3292500.3330727), Tecent, KDD, 2019.

[Personalized Attraction Enhanced Sponsored Search with Multi-task Learning](https://dl.acm.org/doi/pdf/10.1145/3292500.3330659), Alibaba, KDD, 2019.

<a name="Industry_MultiModal"></a>
### Multi-Modal
[PinnerSage: Multi-Modal User Embedding Framework for Recommendations at Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403280), Pinterest Inc., KDD, 2020.

[Investigating Multimodal Features for Video Recommendations at Globoplay](https://dl.acm.org/doi/pdf/10.1145/3383313.3411553), Globo.com, RecSys, 2020. - [Video](https://vimeo.com/455641027)

<a name="Industry_Interpretability"></a>
### Interpretability
[Understanding User Behavior For Document Recommendation](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380071), Microsoft, WWW, 2020.

[Knowing your FATE: Friendship, Action and Temporal Explanations for User Engagement Prediction on Social Apps](https://dl.acm.org/doi/pdf/10.1145/3394486.3403276), Snap, KDD, 2020.

[Counterfactual learning for recommender system](https://dl.acm.org/doi/pdf/10.1145/3383313.3411552), HuaWei, RecSys, 2020. - [Video](https://vimeo.com/455639257)

[Inferring the Causal Impact of New Track Releases on Music Recommendation Platforms through Counterfactual Predictions](https://dl.acm.org/doi/pdf/10.1145/3383313.3418491), Spotify, RecSys, 2020.

<a name="Industry_ColdStart"></a>
### Cold Start 
[The Embeddings That Came in From the Cold: Improving Vectors for New and Rare Products with Content-Based Inference](https://dl.acm.org/doi/pdf/10.1145/3383313.3411477), Coveo, RecSys, 2020. - [Video](https://vimeo.com/455641121)

[CB2CF: A Neural Multiview Content-to-Collaborative Filtering Model for Completely Cold Item Recommendations](https://dl.acm.org/doi/pdf/10.1145/3298689.3347038), Microsoft, RecSys, 2019.

[Preliminary Investigation of Alleviating User Cold-Start Problem in E-commerce with Deep Cross-Domain Recommender System](https://dl.acm.org/doi/pdf/10.1145/3308560.3316596), KDDI Research, Inc, WWW, 2019.

<a name="Industry_Imbalance"></a>
### Imbalance and Limited Labels
[A Dual Heterogeneous Graph Attention Network to Improve Long-Tail Performance for Shop Search in E-Commerce](https://dl.acm.org/doi/pdf/10.1145/3394486.3403393), Alibaba, KDD, 2020.

[Automatic Validation of Textual Attribute Values in E-commerce Catalog by Learning with Limited Labeled Data](https://dl.acm.org/doi/pdf/10.1145/3394486.3403303), Amazon, KDD, 2020.

[Learning with Limited Labels via Momentum Damped & Differentially Weighted Optimization](https://dl.acm.org/doi/pdf/10.1145/3394486.3403394), Spotify & Walmart, KDD, 2020.

[Real-time Attention Based Look-alike Model for Recommender System](https://dl.acm.org/doi/pdf/10.1145/3292500.3330707), Tencent, KDD, 2019.

<a name="Industry_Bias_Correction"></a>
### Bias Correction, Fairness, and Quality
[Ads Allocation in Feed via Constrained Optimization](https://dl.acm.org/doi/pdf/10.1145/3394486.3403391), LinkedIn, KDD, 2020.

[Attribute-based Propensity for Unbiased Learning in Recommender Systems: Algorithm and Case Studies](https://dl.acm.org/doi/pdf/10.1145/3394486.3403285), Google, KDD, 2020.

[Debiasing Grid-based Product Search in E-commerce](https://dl.acm.org/doi/pdf/10.1145/3394486.3403336), LinkedIn, KDD, 2020.

[Improving Recommendation Quality in Google Drive](https://dl.acm.org/doi/pdf/10.1145/3394486.3403341), Google, KDD, 2020.

[Maximizing Cumulative User Engagement in Sequential Recommendation: An Online Optimization Perspective](https://dl.acm.org/doi/pdf/10.1145/3394486.3403329), Alibaba & Microsoft, KDD, 2020.

[User Sentiment as a Success Metric: Persistent Biases Under Full Randomization](https://dl.acm.org/doi/pdf/10.1145/3394486.3403340), Google, KDD, 2020.

[Debiasing Item-to-Item Recommendations With Small Annotated Datasets](https://dl.acm.org/doi/pdf/10.1145/3383313.3412265), Microsoft, RecSys, 2020. - [Video](https://vimeo.com/456912922)

[Unbiased Ad Click Prediction for Position-aware Advertising](https://dl.acm.org/doi/pdf/10.1145/3383313.3412241), HuaWei, RecSys, 2020. - [Video](https://vimeo.com/455946052)

[Unbiased Learning for the Causal Effect of Recommendation](https://arxiv.org/pdf/2008.04563.pdf), Fuji Xerox, RecSys, 2020. - [Video](https://vimeo.com/455956572)

[Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations](https://dl.acm.org/doi/pdf/10.1145/3298689.3346996), Google, RecSys, 2019.

[Fairness in Recommendation Ranking through Pairwise Comparisons](https://dl.acm.org/doi/pdf/10.1145/3292500.3330745), Google, KDD, 2019.

[Fairness-Aware Ranking in Search & Recommendation Systems with Application to LinkedIn Talent Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330691), LinkedIn, KDD, 2019.

[Mathematical Notions vs. Human Perception of Fairness: A Descriptive Approach to Fairness for Machine Learning](https://dl.acm.org/doi/pdf/10.1145/3292500.3330664), KDD, 2019.

[Reinforcement Learning to Optimize Long-term User Engagement in Recommender Systems](https://dl.acm.org/doi/pdf/10.1145/3292500.3330668), JD, KDD, 2019.

<a name="Industry_Privacy"></a>
### Privacy
[From the lab to production: A case study of session-based recommendations in the home-improvement domain](https://dl.acm.org/doi/pdf/10.1145/3383313.3412235), The Home Depot/Relational AI, RecSys, 2020. - [Video](https://vimeo.com/456911397)

[Global and Local Differential Privacy for Collaborative Bandits](https://dl.acm.org/doi/pdf/10.1145/3383313.3412254), Bloomberg, RecSys, 2020. - [Video](https://vimeo.com/455955303)

<a name="Industry_KG_SI"></a>
### Knowledge Graph or Side Information
[Layered Graph Embedding for Entity Recommendation using Wikipedia in the Yahoo! Knowledge Graph](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3383570), Yahoo! Research, KDD, 2020.

[AutoKnow: Self-Driving Knowledge Collection for Products of Thousands of Types](https://dl.acm.org/doi/pdf/10.1145/3394486.3403323), Amazon, KDD, 2020.

[Context-Aware Attentive Knowledge Tracing](https://dl.acm.org/doi/pdf/10.1145/3394486.3403282), Worcester, KDD, 2020.

[Gemini: A Novel and Universal Heterogeneous Graph Information Fusing Framework for Online Recommendations](https://dl.acm.org/doi/pdf/10.1145/3394486.3403388), DiDi, KDD, 2020.

[MultiSage: Empowering GCN with Contextualized Multi-Embeddings on Web-Scale Multipartite Networks](https://dl.acm.org/doi/pdf/10.1145/3394486.3403293), Pinterest Inc., KDD, 2020.

[SimClusters: Community-Based Representations for Heterogeneous Recommendations at Twitter](https://dl.acm.org/doi/pdf/10.1145/3394486.3403370), Twitter, Inc., KDD, 2020.

[Dynamic Heterogeneous Graph Neural Network for Real-time Event Prediction](https://dl.acm.org/doi/pdf/10.1145/3394486.3403373), DiDi, KDD, 2020.

[KRED: Knowledge-Aware Document Representation for News Recommendations](https://dl.acm.org/doi/pdf/10.1145/3383313.3412237), MSRA, RecSys, 2020. - [Video](https://vimeo.com/455949455)

[Variational Low Rank Multinomials for Collaborative Filtering with Side-Information](https://dl.acm.org/doi/pdf/10.1145/3298689.3347036), Netflix, RecSys, 2019.

[Graph Neural Networks for Social Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313488), JD, WWW, 2019.

[Knowledge Graph Convolutional Networks for Recommender Systems](https://dl.acm.org/doi/pdf/10.1145/3308558.3313417), MSRA, WWW, 2019.

[Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313411), Microsoft, WWW, 2019.

[IntentGC: a Scalable Graph Convolution Framework Fusing Heterogeneous Information for Recommendation](https://dl.acm.org/doi/pdf/10.1145/3292500.3330686), Alibaba, KDD, 2019.

[Metapath-guided Heterogeneous Graph Neural Network for Intent Recommendation](https://dl.acm.org/doi/pdf/10.1145/3292500.3330673), Alibaba, KDD, 2019.

<a name="Industry_Transfer"></a>
### Transfer Learning or Multi-Task Learning
[Deep Transfer Learning for Search and Recommendation](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3383115), LinkedIn, WWW, 2020. - [Slides](https://docs.google.com/presentation/d/1YbHIwiKpIbgRh-NsMzpE3r4M4m3HB_0C8ajZhhQWJKc/present?slide=id.g7ec9d4a572_9_715)

[General-Purpose User Embeddings based on Mobile App Usage](https://dl.acm.org/doi/pdf/10.1145/3394486.3403334), Tecent, KDD, 2020.

[GrokNet: Unified Computer Vision Model Trunk and Embeddings For Commerce](https://dl.acm.org/doi/pdf/10.1145/3394486.3403311), Facebook, KDD, 2020.

[Jointly Learning to Recommend and Advertise](https://dl.acm.org/doi/pdf/10.1145/3394486.3403384), ByteDance, KDD, 2020.

[Learning to Generate Personalized Query Auto-Completions via a Multi-View Multi-Task Attentive Approach](https://dl.acm.org/doi/pdf/10.1145/3394486.3403350), Alibaba, KDD, 2020.

[M2GRL: A Multi-task Multi-view Graph Representation Learning Framework for Web-scale Recommender Systems](https://dl.acm.org/doi/pdf/10.1145/3394486.3403284), Alibaba, KDD, 2020.

[Recommending What Video to Watch Next: A Multitask Ranking System](https://dl.acm.org/doi/pdf/10.1145/3298689.3346997), Google, RecSys, 2019.

[Domain Adaptation in Display Advertising: An Application for Partner Cold-Start](https://dl.acm.org/doi/pdf/10.1145/3298689.3347004), Criteo AI Labs, RecSys, 2019.

[Jointly Leveraging Intent and Interaction Signals to Predict User Satisfaction with Slate Recommendations](https://dl.acm.org/doi/pdf/10.1145/3308558.3313613), Spotify, WWW, 2019.

[Multi-Task Feature Learning for Knowledge Graph Enhanced Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313411), Microsoft, WWW, 2019.

[Finding Users Who Act Alike: Transfer Learning for Expanding Advertiser Audiences](https://dl.acm.org/doi/pdf/10.1145/3292500.3330714), Pinterest, KDD, 2019.

[Learning a Unified Embedding for Visual Search at Pinterest](https://dl.acm.org/doi/pdf/10.1145/3292500.3330739), Pinterest, KDD, 2019.

[Personalized Attraction Enhanced Sponsored Search with Multi-task Learning](https://dl.acm.org/doi/pdf/10.1145/3292500.3330659), Alibaba, KDD, 2019.

[PinText: A Multitask Text Embedding System in Pinterest](https://dl.acm.org/doi/pdf/10.1145/3292500.3330671), Pinterest, KDD, 2019.

[CCCFNet: A Content-Boosted Collaborative Filtering Neural Network for Cross Domain Recommender Systems](https://www.microsoft.com/en-us/research/uploads/prod/2019/07/pp004-lian.pdf), Microsoft Research, WWW, 2017.


<a name="Industry_FE"></a>
### Feature Engineering
[Future Data Helps Training: Modeling Future Contexts for Session-based Recommendation](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380116), Tecent, WWW, 2020.

[AutoFIS: Automatic Feature Interaction Selection in Factorization Models for Click-Through Rate Prediction](https://dl.acm.org/doi/pdf/10.1145/3394486.3403314), Huawei, KDD, 2020.

[Comprehensive Information Integration Modeling Framework for Video Titling](https://dl.acm.org/doi/pdf/10.1145/3394486.3403325), Alibaba, KDD, 2020.

[Temporal-Contextual Recommendation in Real-Time](https://dl.acm.org/doi/pdf/10.1145/3394486.3403278), Amazon AWS, KDD, 2020.

[TIES: Temporal Interaction Embeddings for Enhancing Social Media Integrity at Facebook](https://dl.acm.org/doi/pdf/10.1145/3394486.3403364), Facebook, KDD, 2020.

[FiBiNET: Combining Feature Importance and Bilinear Feature Interaction for Click-Through Rate Prediction](https://dl.acm.org/doi/pdf/10.1145/3298689.3347043), Sina Weibo Inc., RecSys, 2019.

[“Who doesn’t like dinosaurs?” Finding and Eliciting Richer Preferences for Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3412267), MSR, RecSys, 2020. - [Video](https://vimeo.com/455956459)

<a name="Industry_CompAds"></a>
### Computational Ads
[A Request-level Guaranteed Delivery Advertising Planning: Forecasting and Allocation](https://dl.acm.org/doi/pdf/10.1145/3394486.3403348), Tencent, KDD, 2020.

[Category-Specific CNN for Visual-aware CTR Prediction at JD.com](https://dl.acm.org/doi/pdf/10.1145/3394486.3403319), JD, KDD, 2020.

[Combo-Attention Network for Baidu Video Advertising](https://dl.acm.org/doi/pdf/10.1145/3394486.3403297), Baidu Search Ads, KDD, 2020.

[MultiRec: A Multi-Relational Approach for Unique Item Recommendation in Auction Systems](https://dl.acm.org/doi/pdf/10.1145/3383313.3412242), Volkswagen Financial Services AG, RecSys, 2020. - [Video](https://vimeo.com/455953054)

[Smart Targeting: A Relevance-driven and Configurable Targeting Framework for Advertising System](https://dl.acm.org/doi/pdf/10.1145/3383313.3418481), JD, RecSys, 2020. 

[Recommending Themes for Ad Creative Design via Visual-Linguistic Representations](https://dl.acm.org/doi/pdf/10.1145/3366423.3380001), Yahoo Research, WWW, 2020.

[Addressing Delayed Feedback for Continuous Training with Neural Networks in CTR prediction](https://dl.acm.org/doi/pdf/10.1145/3298689.3347002), Twitter, RecSys, 2019.

[A Unified Framework for Marketing Budget Allocation](https://dl.acm.org/doi/pdf/10.1145/3292500.3330700), Alibaba, KDD, 2019.

[AiAds: Automated and Intelligent Advertising System for Sponsored Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330782), Baidu, KDD, 2019.

[Bid Optimization by Multivariable Control in Display Advertising](https://dl.acm.org/doi/pdf/10.1145/3292500.3330681), Alibaba, KDD, 2019.

[Carousel Ads Optimization in Yahoo Gemini Native](https://dl.acm.org/doi/pdf/10.1145/3292500.3330740), Yahoo, KDD, 2019.

[Conversion Prediction Using Multi-task Conditional Attention Networks to Support the Creation of Effective Ad Creatives](https://dl.acm.org/doi/pdf/10.1145/3292500.3330789), Gunosy Inc, KDD, 2019.

[Deep Spatio-Temporal Neural Networks for Click-Through Rate Prediction](https://dl.acm.org/doi/pdf/10.1145/3292500.3330655), Alibaba, KDD, 2019.

[MOBIUS: Towards the Next Generation of Query-Ad Matching in Baidu’s Sponsored Search](https://dl.acm.org/doi/pdf/10.1145/3292500.3330651), Baidu, KDD, 2019.

[Practice on Long Sequential User Behavior Modeling for Click-Through Rate Prediction](https://dl.acm.org/doi/pdf/10.1145/3292500.3330666), Alibaba, KDD, 2019.

[Predicting Different Types of Conversions with Multi-Task Learning in Online Advertising](https://dl.acm.org/doi/pdf/10.1145/3292500.3330783), Verizon Media, KDD, 2019.

[Recurrent Neural Networks for Stochastic Control in Real-Time Bidding](https://dl.acm.org/doi/pdf/10.1145/3292500.3330749), Verizon Media, KDD, 2019.

<a name="Industry_Travel"></a>
### Travel and Delivery
[When Recommender Systems Meet Fleet Management: Practical Study in Online Driver Repositioning System](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380287), DiDi, WWW, 2020.

[BusTr: Predicting Bus Travel Times from Real-Time Traffic](https://dl.acm.org/doi/pdf/10.1145/3394486.3403376), Google Research, KDD, 2020

[CompactETA: A Fast Inference System for Travel Time Prediction](https://dl.acm.org/doi/pdf/10.1145/3394486.3403386), DiDi, KDD, 2020.

[ConSTGAT: Contextual Spatial-Temporal Graph Attention Network for Travel Time Estimation at Baidu Maps](https://dl.acm.org/doi/pdf/10.1145/3394486.3403320), Baidu, KDD, 2020.

[Delivery Scope: A New Way of Restaurant Retrieval For On-demand Food Delivery Service](https://dl.acm.org/doi/pdf/10.1145/3394486.3403353), MeiTuan, KDD, 2020.

[Doing in One Go: Delivery Time Inference Based on Couriers’ Trajectories](https://dl.acm.org/doi/pdf/10.1145/3394486.3403332), JD, KDD, 2020.

[Efficiently Solving the Practical Vehicle Routing Problem: A Novel Joint Learning Approach](https://dl.acm.org/doi/pdf/10.1145/3394486.3403356), Alibaba, KDD, 2020.

[HetETA: Heterogeneous Information Network Embedding for Estimating Time of Arrival](https://dl.acm.org/doi/pdf/10.1145/3394486.3403294), DiDi, KDD, 2020.

[Hybrid Spatio-Temporal Graph Convolutional Network: Improving Traffic Prediction with Navigation Data](https://dl.acm.org/doi/pdf/10.1145/3394486.3403358), Alibaba, KDD, 2020.

[Predicting Individual Treatment Effects of Large-scale Team Competitions in a Ride-sharing Economy](https://dl.acm.org/doi/pdf/10.1145/3394486.3403286), DiDi, KDD, 2020.

[A Collaborative Learning Framework to Tag Refinement for Points of Interest](https://dl.acm.org/doi/pdf/10.1145/3292500.3330698), Baidu, KDD, 2019.

[Hydra: A Personalized and Context-Aware Multi-Modal Transportation Recommendation System](https://dl.acm.org/doi/pdf/10.1145/3292500.3330660), Baidu Research, KDD, 2019.

<a name="Industry_Others"></a>
### Others
[MetaSelector: Meta-Learning for Recommendation with User-Level Adaptive Model Selection](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3379999), Huawei, WWW, 2020.

[Off-policy Learning in Two-stage Recommender Systems](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380130), Google AI, WWW, 2020.

[PARS: Peers-aware Recommender System](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380013), Alibaba, WWW, 2020.

[Attentive Sequential Models of Latent Intent for Next Item Recommendation](https://dl.acm.org/doi/pdf/10.1145/3366423.3380002), Etsy, WWW, 2020.

[Taming Pretrained Transformers for Extreme Multi-label Text Classification](https://dl.acm.org/doi/pdf/10.1145/3394486.3403368), Amazon, KDD, 2020.

[Building Continuous Integration Services for Machine Learning](https://dl.acm.org/doi/pdf/10.1145/3394486.3403290), Microsoft, KDD, 2020.

[Learning Representations of Hierarchical Slates in Collaborative Filtering](https://dl.acm.org/doi/pdf/10.1145/3383313.3418484), Netflix, RecSys, 2020.

[Goal-driven Command Recommendations for Analysts](https://dl.acm.org/doi/pdf/10.1145/3383313.3412255), Adobe Research, RecSys, 2020. - [Video](https://vimeo.com/455956170)

[A Recommender System for Heterogeneous and Time Sensitive Environment](https://dl.acm.org/doi/pdf/10.1145/3298689.3347039), Electronic Arts, Inc., RecSys, 2019. 

[GhostLink: Latent Network Inference for Influence-aware Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313449), Amazon, WWW, 2019.

[Characterizing and Forecasting User Engagement with In-app Action Graph: A Case Study of Snapchat](https://dl.acm.org/doi/pdf/10.1145/3292500.3330750), Snapchat, KDD, 2019.

[Gmail Smart Compose: Real-Time Assisted Writing](https://dl.acm.org/doi/pdf/10.1145/3292500.3330723), Google, KDD, 2019.

<a name="Industry_Other_Theory"></a>
#### Theory
[MetaSelector: Meta-Learning for Recommendation with User-Level Adaptive Model Selection](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3379999), Huawei, WWW, 2020.

[Leveraging Behavioral Heterogeneity Across Markets for Cross-Market Training of Recommender Systems](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3384362), Spotify, WWW, 2020.

[PARS: Peers-aware Recommender System](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380013), Alibaba, WWW, 2020.

[Mixed Negative Sampling for Learning Two-tower Neural Networks in Recommendations](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366424.3386195), Google, WWW, 2020.

[Attentive Sequential Models of Latent Intent for Next Item Recommendation](https://dl.acm.org/doi/pdf/10.1145/3366423.3380002), Etsy, WWW, 2020.

[CLARA: Confidence of Labels and Raters](https://dl.acm.org/doi/pdf/10.1145/3394486.3403304), Facebook, KDD, 2020.

[Geodemographic Influence Maximization](https://dl.acm.org/doi/pdf/10.1145/3394486.3403327), Baidu, KDD, 2020.

[Hypergraph Convolutional Recurrent Neural Network](https://dl.acm.org/doi/pdf/10.1145/3394486.3403389), KAIST, KDD, 2020.

[Multi-objective Optimization for Guaranteed Delivery in Video Service Platform](https://dl.acm.org/doi/pdf/10.1145/3394486.3403352), Alibaba, KDD, 2020.

[A Human Perspective on Algorithmic Similarity](https://dl.acm.org/doi/pdf/10.1145/3383313.3411549), Netflix, RecSys, 2020. - [Video](https://vimeo.com/455640996)

[Deconstructing the Filter Bubble: User Decision-Making and Recommender Systems](https://dl.acm.org/doi/pdf/10.1145/3383313.3412246), Everquote, RecSys, 2020. - [Video](https://vimeo.com/455947278)

[Uplif-based Evaluation and Optimization of Recommenders](https://dl.acm.org/doi/pdf/10.1145/3298689.3347018), Fuji Xerox, RecSys, 2019.

[Towards Neural Mixture Recommender for Long Range Dependent User Sequences](https://dl.acm.org/doi/pdf/10.1145/3308558.3313650), Google, WWW, 2019.

[Hierarchical Temporal Convolutional Networks for Dynamic Recommender Systems](https://dl.acm.org/doi/pdf/10.1145/3308558.3313747), Pinterest, WWW, 2019.

[A Generalized Framework for Population Based Training](https://dl.acm.org/doi/pdf/10.1145/3292500.3330649), DeepMind, KDD, 2019.

[FDML: A Collaborative Machine Learning Framework for Distributed Features](https://dl.acm.org/doi/pdf/10.1145/3292500.3330765), Tecent, KDD, 2019.

[Optuna: A Next-generation Hyperparameter Optimization Framework](https://dl.acm.org/doi/pdf/10.1145/3292500.3330701), Preferred Networks, Inc., KDD, 2019.

[Sequential Scenario-Specific Meta Learner for Online Recommendation](https://dl.acm.org/doi/pdf/10.1145/3292500.3330726), Alibaba, KDD, 2019.

[Whole Page Optimization with Global Constraints](https://dl.acm.org/doi/pdf/10.1145/3292500.3330675), Amazon, KDD, 2019.

<a name="Industry_Other_Fashion"></a>
#### Fashion Recommendation
[OutfitNet: Fashion Outfit Recommendation with Attention-Based Multiple Instance Learning](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380096), VISA Research, WWW, 2020.

[Bootstrapping Complete The Look at Pinterest](https://dl.acm.org/doi/pdf/10.1145/3394486.3403382), Pinterest, KDD, 2020.

[A Deep Learning System for Predicting Size and Fit in Fashion](https://dl.acm.org/doi/pdf/10.1145/3298689.3347006), Zalando, RecSys, 2019.

[Shop your Right Size: A System for Recommending Sizes for Fashion products](https://dl.acm.org/doi/pdf/10.1145/3308560.3316599), Myntra Designs, WWW, 2019.

[Personalized Bundle List Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308558.3313568), Alibaba, WWW, 2019.

[Concept to Code: Deep Learning for Fashion Recommendation](https://dl.acm.org/doi/pdf/10.1145/3308560.3320100), Flipkart, WWW, 2019.

[POG: Personalized Outfit Generation for Fashion Recommendation at Alibaba iFashion](https://dl.acm.org/doi/pdf/10.1145/3292500.3330652), Alibaba, KDD, 2019.

<a name="Industry_Other_e-commerce"></a>
#### E-Commerce
[Keywords Generation Improves E-Commerce Session-based Recommendation](https://dl-acm-org.libproxy.utdallas.edu/doi/pdf/10.1145/3366423.3380232), JD, WWW, 2020.

[Exploring Clustering of Bandits for Online Recommendation System](https://dl.acm.org/doi/pdf/10.1145/3383313.3412250), Tencent, RecSys, 2020. - [Video](https://vimeo.com/455953183)

[Learning to Collaborate in Multi-Module Recommendation via Multi-Agent Reinforcement Learning without Communication](https://arxiv.org/pdf/2008.09369.pdf), Alibaba, RecSys, 2020. - [Video](https://vimeo.com/455948668)

[A Pareto-Eficient Algorithm for Multiple Objective Optimization in E-Commerce Recommendation](https://dl.acm.org/doi/pdf/10.1145/3298689.3346998), Alibaba & Kuai, RecSys, 2019.

[Anomaly Detection for an E-commerce Pricing System](https://dl.acm.org/doi/pdf/10.1145/3292500.3330748), Walmart, KDD, 2019.

[Buying or Browsing? : Predicting Real-time Purchasing Intent using Attention-based Deep Network with Multiple Behavior](https://dl.acm.org/doi/pdf/10.1145/3292500.3330670), Alibaba, KDD, 2019.

[Infer Implicit Contexts in Real-time Online-to-Offline Recommendation](https://dl.acm.org/doi/pdf/10.1145/3292500.3330716), Alibaba, KDD, 2019.

[MSURU: Large Scale E-commerce Image Classification With Weakly Supervised Search Data](https://dl.acm.org/doi/pdf/10.1145/3292500.3330696), Facebook, KDD, 2019.

[Online Purchase Prediction via Multi-Scale Modeling of Behavior Dynamics](https://dl.acm.org/doi/pdf/10.1145/3292500.3330790), JD, KDD, 2019.

[Understanding the Role of Style in E-commerce Shopping](https://dl.acm.org/doi/pdf/10.1145/3292500.3330760), Twitter, KDD, 2019.

## Academic Papers
<a name="Academic_Scalability"></a>
### 2018
[[IJCAI](https://www.ijcai.org/Proceedings/2018/0510.pdf)] NeuRec: On Nonlinear Transformation for Personalized Ranking [__`mlp.`__, __`per.`__， __`ran.`__]

### 2017
[[WWW](https://arxiv.org/pdf/1708.05031.pdf)] Neural Collaborative Filtering [__`mlp.`__] :fire:

[[SIGIR](https://arxiv.org/pdf/1706.03205.pdf)] Item Silk Road: Recommending Items from Information Domains to Social Users [__`mlp.`__,__`tra.`__] :star:

[[IJCAI](https://www.ijcai.org/Proceedings/2017/0447.pdf)] Deep Matrix Factorization Models for Recommender Systems [__`mlp.`__] :fire:

[[SIGIR](https://arxiv.org/pdf/1708.05027.pdf)] Neural Factorization Machines for Sparse Predictive Analytics [__`mlp`__] :fire:

### 2015
[[Arxiv](https://arxiv.org/pdf/1511.06443.pdf)] Neural network matrix factorization. [__`mlp.`__] :star:

## Special Topics
### Transformers in Recommendation and Ranking System
[Taming Pretrained Transformers for Extreme Multi-label Text Classification](https://dl.acm.org/doi/pdf/10.1145/3394486.3403368), Amazon, KDD, 2020.

[SSE-PT: Sequential Recommendation Via Personalized Transformer](https://dl.acm.org/doi/pdf/10.1145/3383313.3412258), RecSys, 2020. - [Video](https://vimeo.com/455947093)

[What does BERT know about books, movies and music? Probing BERT for Conversational Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3412249), RecSys, 2020. - [Video](https://vimeo.com/455951047)

[BERT, ELMo, USE and InferSent Sentence Encoders: The Panacea for Research-Paper Recommendation?](http://ceur-ws.org/Vol-2431/paper2.pdf), RecSys, 2019.

### AR/VR 
[In-Store Augmented Reality-Enabled Product Comparison and Recommendation](https://dl.acm.org/doi/pdf/10.1145/3383313.3412266), RecSys, 2020. - [Video](https://vimeo.com/455946175)

[Nostalgin: Extracting 3D City Models from Historical Image Data](https://dl.acm.org/doi/pdf/10.1145/3292500.3330743), Google, KDD, 2019.
