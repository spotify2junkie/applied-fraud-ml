
# applied-risk-ml
Meticulously selected papers, articles, and blogs on the implementation of data science and machine learning in risk-related industries. This project is inspired by [applied-ml](https://github.com/eugeneyan/applied-ml?tab=readme-ov-file#feature-stores).

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](./CONTRIBUTING.md)

**Table of Contents**

- [applied-risk-ml](#applied-risk-ml)
  - [Community Detection](#community-detection)
  - [Anomaly Detection](#anomaly-detection)
  - [GNN](#gnn)
  - [Sequential Modeling](#sequential-modeling)
  - [TabularDNN](#tabulardnn)
  - [Others](#others)

## Community Detection

| Title                                                                                                                                      | Year | Company  | Fields Applied    |
|--------------------------------------------------------------------------------------------------------------------------------------------|------|----------|-------------------|
| [Uncovering Large Groups of Active Malicious Accounts in Online Social Networks](https://dl.acm.org/doi/10.1145/2660267.2660269)            | 2015 | Meta     | Account Fraud     |
| [Detecting Fake Accounts in Online Social Networks at the Time of Registrations](https://people.duke.edu/~zg70/papers/Ianus.pdf)            | 2019 | Tencent  | Account Fraud     |
| [Similarity clustering to catch fraud rings](https://stripe.com/blog/similarity-clustering)                                                | 2020 | Stripe   | Transaction Fraud |
| [Detecting fake accounts on social networks with SybilEdge](https://research.facebook.com/blog/2020/4/detecting-fake-accounts-on-social-networks-with-sybiledge/) | 2020 | Meta     | Account Fraud     |
| [Unveiling Fake Accounts at the Time of Registration: An Unsupervised Approach](https://dl.acm.org/doi/abs/10.1145/3447548.3467094)          | 2021 | Tencent  | Account Fraud     |

## Anomaly Detection

| Title                                                                                                                                                               | Year | Company     | Fields Applied    |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|-------------|-------------------|
| [FARE: Schema-Agnostic Anomaly Detection in Social Event Logs](https://research.snap.com/publications/publication.html#fare--schema-agnostic-anomaly-detection-in-social-event-logs) | 2019 | Snap        | Bot Detection     |
| [Detecting Fake Accounts in Online Social Networks at the Time of Registrations](https://people.duke.edu/~zg70/papers/Ianus.pdf)                                    | 2019 | Tencent     | Account Fraud     |
| [Cloudflare Bot Management: machine learning and more](https://blog.cloudflare.com/cloudflare-bot-management-machine-learning-and-more/)                        | 2020 | Cloudflare  | Bot Detection     |
| [Unveiling Fake Accounts at the Time of Registration: An Unsupervised Approach](https://dl.acm.org/doi/abs/10.1145/3447548.3467094)                                 | 2021 | Tencent     | Account Fraud     |
| [Machine Learning for Fraud Detection in Streaming Services](https://netflixtechblog.com/machine-learning-for-fraud-detection-in-streaming-services-b0b4ef3be3f6)   | 2022 | Netflix     | Account Fraud     |
| [Project RADAR: Intelligent Early Fraud Detection System with Humans in the Loop](https://www.uber.com/en-HK/blog/project-radar-intelligent-early-fraud-detection/?uclick_id=f8dcba03-bc8f-4564-bd88-fc9b91ffbdf2) | 2022 | Uber        | Customer Fraud    |
| [Unsupervised and semi-supervised anomaly detection with data-centric ML – Google Research Blog](https://blog.research.google/2023/02/unsupervised-and-semi-supervised.html) | 2023 | Google      |                   |
| [Risk Entity Watch – Using Anomaly Detection to Fight Fraud](https://www.uber.com/en-HK/blog/risk-entity-watch/)                                                   | 2023 | Uber        | Customer Fraud    |

## GNN

| Title                                                                                                                    | Year | Company       | Fields Applied    |
|--------------------------------------------------------------------------------------------------------------------------|------|---------------|-------------------|
| [GeniePath: Graph Neural Networks with Adaptive Receptive Paths](https://export.arxiv.org/pdf/1802.00910)                  | 2018 | Ant Financial | payment fraud     |
| [Spam Review Detection with Graph Convolutional Networks](https://zhuanlan.zhihu.com/p/94138184)                           | 2019 | Alibaba       | content moderation |
| [TitAnt: Online Real-time Transaction Fraud Detection in Ant Financial](https://arxiv.org/pdf/1906.07407.pdf)             | 2019 | Ant Finance   | Transaction Fraud |
| [Suspicious Massive Registration Detection Via Dynamic Heterogeneous Graph Neural Network](https://arxiv.org/pdf/2012.10831.pdf) | 2020 | Ant Financial | Account Fraud     |
| [Financial Risk Analysis for SMEs with Graph-based Supply Chain Mining](https://www.ijcai.org/proceedings/2020/0643.pdf) | 2020 | Ant Financial | Financial Risk    |
| [Uncovering Insurance Fraud Conspiracy with Network Learning](https://arxiv.org/pdf/2002.12789.pdf)                      | 2020 | Ant Financial | Customer Fraud    |
| [Heterogeneous Mini-Graph Neural Network and Its Application to Fraud Invitation Detection](https://cs.nju.edu.cn/liyf/paper/icdm20-hmgnn.pdf) | 2020 | Iqiyi         | Customer Fraud    |
| [BotSpot: A Hybrid Learning Framework to Uncover Bot Install Fraud in Mobile Advertising](https://dl.acm.org/doi/10.1145/3340531.3412690) | 2021 | Mobvisa       | Bot Detection     |
| [Fraud Detection: Using Relational Graph Learning to Detect Collusion](https://www.uber.com/en-HK/blog/fraud-detection/?uclick_id=62458e63-cb2b-4963-a8a8-c87f62ff3553) | 2021 | Uber          | Customer Fraud    |
| [How Pinterest fights misinformation, hate speech, and self-harm content with machine learning](https://medium.com/pinterest-engineering/how-pinterest-fights-misinformation-hate-speech-and-self-harm-content-with-machine-learning-1806b73b40ef) | 2021 | Pinterest     | content moderation |
| [Graph Usage in Combating ATO Fraud Risk](https://medium.com/paypal-tech/graph-usage-in-combating-ato-fraud-risk-6dafbe5cc3e5) | 2023 | Paypal        | Account Fraud     |

## Sequential Modeling

| Title                                                                                                                                                               | Year | Company     | Fields Applied    |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|-------------|-------------------|
| [DeepTrax: Embedding Graphs of Financial Transactions](https://arxiv.org/pdf/1907.07225.pdf)                                                                      | 2019 | Capital One | Transaction Fraud |
| [Using deep learning to detect abusive sequences of member activity](https://www.linkedin.com/blog/engineering/trust-and-safety/using-deep-learning-to-detect-abusive-sequences-of-member-activi) | 2021 | Linkedin    | Customer Fraud    |
| [Explainable Deep Behavioral Sequence Clustering for Transaction Fraud Detection](https://www.notion.so/Explainable-Deep-Behavioral-Sequence-Clustering-for-Transaction-Fraud-Detection-d5fb14ccd9e24d75b9a926ab242326a9?pvs=21) | 2021 | Ebay        | Customer Fraud    |
| [User Behavior Pre-training for Online Fraud Detection](https://dl.acm.org/doi/pdf/10.1145/3534678.3539126)                                                       | 2022 | Alibaba     | Customer Fraud    |
| [Graph Embeddings and Similarity Search in ML](https://www.capitalone.com/tech/machine-learning/similarity-search-graph-embeddings/)                                 | 2023 | Capital One | Transaction Fraud |

## TabularDNN

| Title                                                                                                                                                               | Year | Company   | Fields Applied       |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|-----------|----------------------|
| [BotSpot: A Hybrid Learning Framework to Uncover Bot Install Fraud in Mobile Advertising](https://dl.acm.org/doi/10.1145/3340531.3412690)                          | 2021 | Mobvisa   | Bot Detection        |
| [How WhatsApp fights Spam & Abuse](https://docs.google.com/presentation/d/1W0sjPiNxNJIDUrW8FiEVkdeDpQll7ArTWSQk7u1fl2E/edit?pli=1#slide=id.p23)                          | 2021 | Whatsapp | Content Moderation  |
| [How Pinterest Fights Spam Using Machine Learning](https://medium.com/pinterest-engineering/how-pinterest-fights-spam-using-machine-learning-d0ee2589f00a)        | 2021 | Pinterest | Content Moderation  |
| [Amazon Science --- Invalidating robotic ad clicks in real time - Amazon Science](https://www.amazon.science/blog/invalidating-robotic-ad-clicks-in-real-time) | 2023 | Amazon    | Bot Detection        |
| **[How we built it: Stripe Radar](https://stripe.com/blog/how-we-built-it-stripe-radar)**                                                                          | 2023 | Stripe    | Transaction Fraud    |

## Others

| Title                                                                                                                                                               | Year | Company   | Fields Applied      |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|-----------|---------------------|
| [Fighting Financial Fraud with Targeted Friction](https://medium.com/airbnb-engineering/fighting-financial-fraud-with-targeted-friction-82d950d8900e)              | 2018 | Airbnb    | Chargeback          |
| [Here's how we're using AI to help detect misinformation](https://ai.meta.com/blog/heres-how-were-using-ai-to-help-detect-misinformation/)                          | 2020 | Meta      | Content Moderation  |
| [Understanding the intentions of Child Sexual Abuse Material (CSAM) sharers - Meta Research](https://research.facebook.com/blog/2021/2/understanding-the-intentions-of-child-sexual-abuse-material-csam-sharers/) | 2021 | Meta | Content Moderation  |
| [Bandits for Online Calibration: An Application to Content Moderation on Social Media Platforms](https://arxiv.org/abs/2211.06516)                                   | 2022 | Meta      | Content Moderation  |
| [Viral spam content detection at LinkedIn](https://www.linkedin.com/blog/engineering/trust-and-safety/viral-spam-content-detection-at-linkedin)                   | 2023 | Linkedin  | Content Moderation  |
| [Announcing Cloudflare Fraud Detection](https://blog.cloudflare.com/cloudflare-fraud-detection/)                                                                    | 2023 | Cloudflare| Bot Detection       |
| [Variable Hub: Easier Data Integration for Risk Decisioning](https://innovation.ebayinc.com/tech/engineering/variable-hub-easier-data-integration-for-risk-decisioning/) | 2023 | Ebay      | CyberAttack         |
