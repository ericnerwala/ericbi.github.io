# Eric Bi

# High School Bioinformatics/Machine Learning Researcher 

#### Technical Skills: Python, C++, JavaScript, MATLAB

## Education
- High School Student | The Webb Schools of California (_June 2021_)              		
- Middle School Student	| The Middle School Affiliated to Shandong University (_Sept 2018_)	 			        		

## Honors & Awards
**Computer Science / Bioinformatics**
- 73rd LA Science Fair Computer Science Category Second Place 
- Second Author of AMIA 2024 Annual Symposium Paper (Top 20% / 1400)
- USACO Platinum Division Qualifier
- AIME Qualifier (AMC12 126/150, AIME 9/15)

## Projects
### WebbGPT (My high school LLM)
[Colab Link](https://colab.research.google.com/github/ericnerwala/LLaMA-Factory/blob/main/WebbGPT_with_LLaMA_Factory.ipynb#scrollTo=1oHFCsV0z-Jw!)

My mailbox is often overwhelmed by upcoming deadlines and grade reports, making it difficult to follow communities I care about--weekend runs, club activities, classmates’ sports matches, and outreach programs. I knew I was not alone in feeling this way.  My subsequent idea for creating WebbGPT--The Webb Schools scheduling chatbot--reached an easy consensus at the monthly meeting of Computer Science Club because of its potential value to our community. We dreamed for a future where students never hear about a club event after-the-fact or miss supporting a home tennis match..  Using LLaMA-3, we trained the chatbot on data from the school's official website, but early versions performed poorly due to outdated and generic content. Drawing from my experience in natural language processing, I shifted our approach to focus on student inbox data, which better reflected the real needs of our community. Over five months, we refined WebbGPT, feeding it relevant information from class updates, event reminders, and newsletters.  The final release was a success, transforming how students access information about school activities. WebbGPT now serves as a hub for details on lunch menus, club events, volunteer opportunities, and more, making our community more connected and informed.   

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### 2)	BadCLM: Backdoor Attack in Clinical Language Models for Electronic Health Records
[Publication](https://arxiv.org/abs/2407.05213)

The advent of clinical language models integrated into electronic health records (EHR) for clinical decision support has marked a significant advancement, leveraging the depth of clinical notes for improved decision-making. Despite their success, the potential vulnerabilities of these models remain largely unexplored. This paper delves into the realm of backdoor attacks on clinical language models, introducing an innovative attention-based backdoor attack method, BadCLM. This technique clandestinely embeds a backdoor within the models, causing them to produce incorrect predictions when a pre-defined trigger is present in inputs, while functioning accurately otherwise. We demonstrate the efficacy of BadCLM through an in-hospital mortality prediction task with MIMIC III dataset, showcasing its potential to compromise model integrity. Our findings illuminate a significant security risk in clinical decision support systems and pave the way for future endeavors in fortifying clinical language models against such vulnerabilities.
![Bike Study](/assets/img/bike_study.jpeg)

## Using Pretrained Natural Language Model to Extract Drug-Drug-Interaction from Medical Document

The advancement in medicine has resulted in the creation of numerous drugs in recent years, but the interactions between these new drugs are not well understood. Limited medical knowledge among the general public makes it difficult for them to comprehend the complex information contained in professional papers on drug-drug interactions (DDIs), leading to potential misunderstandings with severe consequences. To solve this issue, I present an end-to-end system for extracting DDIs from medical papers, providing people with accurate information mined from vast research documents. The system applies a Name Entity Recognition toolkit to identify all drugs mentioned in an article and then uses a Relation Extraction model to classify any interactions between the drugs. The Relation Extraction model is constructed using sentence embeddings generated from Bidirectional Encoder Representations from Transformers (BERT) and improved by incorporating grammatical features through Graph Convolution Network on sentence dependency trees. The model outperforms the baseline BERT model, achieving a macro-averaged F1-score of 0.85 on binary classification tasks. To further assist people in understanding DDIs, the author also created a knowledge graph-based database including COVID-19-related DDIs extracted from PubMed.

## Publications
1. Lyu, W., Bi, Z., Wang, F., & Chen, C. (2024). BadCLM: Backdoor Attack in Clinical Language Models for Electronic Health Records. arXiv preprint arXiv:2407.05213.

