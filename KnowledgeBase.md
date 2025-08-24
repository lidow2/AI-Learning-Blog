Knowledge is a library of 

Generally we use the coze to call the knowledge base in China
After logging in, act in the following way:
work space -> resource library -> + resource
as the pic shows
![图片描述](/images/coze/create knowledge base.png)

Name it (I named my knowledge base as "AI LLM" and select the "text" as the importing type
![图片描述](/images/coze/type of knowledge base.png)

Select a file to upload


If the file you upload is a paper, click "Hierarchical Segmentation"
If a general file, click customization
set the parameters according to the following setting

then the sentence would be separated in a proper way

By the way, the parameter "​​Segment Overlap Ratio" means the ratio that the machine can recognize to retrieve the correct sentences

Then, if you want to add some info at this step, click 

Here, we use bulk insert to import the urls in doc file (the root url) of deepseek api


Again, set the "customization" as Segment Identifier



Way of creating an agent
(9)

click
(10)

set the parameter of the knowledge base
searching strategy: 
1. Semantics: Search by the text relevance
   For an example, if you input Chinese, its corresponding English meaning would also appear in the output result
2. Full text: If you hope the output result would be highly relevant to the prompt, it's a good choice
3. Mix: Combine the features of the above two
 ​
(11)
