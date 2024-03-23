This dataset is being created by focusing on reducing the noisy data. In a news headline, a sentence consists of a lower number of unusable data than a full news corpus. So for this, we try to make a new dataset with a low number of unusable data only annotating the news headline. This also implies that our datasets are different from existing work on Bangla NER. We collected data from Bangladeshi Popular online newspapers Juganthor, Prothom Alo, etc. The dataset consists of 20,000 sentences. We cover five types of topics such as politics, crime, sports, entertainment, and international news. For annotation, we followed the IOB2 tag formatting. In IOB2 format each word is defined with a certain entity type. It represents whether the token is either inside an entity (defined as “I-”), or at the beginning of an entity (defined as a “B-”), or outside the entity (defined as “O-”). For instance, a person name is defined as B-PER, I-PER, O-PER while a location name is defined as B-LOC, I-LOC, O-LOC. In our dataset, each headline consists different type word and each word has an entity but in this approach, we define six entity types. The annotated entity types include the following:
Person --> PER
Location --> LOC
Organization --> ORG
Units --> UNIT
Time --> TIME
Miscellaneous -->0


**Dataset details:**

Total Sentence is: 4364
Total Word is: 23870
Total Unusable word is: 15688

||Person  | Location  | Organization | Time | Unit|
| ---- | --- | --- | --- | --- | --- |
|Single Words|1704|2303|519|127|935|
|Double Words|207|68|81|215|226|
|Multiple Words|12|8|43|8|269|

