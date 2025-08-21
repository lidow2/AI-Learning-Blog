# AI-Learning-Blog
A. Some advices for using DeepSeek-R1
1. Set the tempearture within the range of 0.5-0.7 (0.6 is recommended), to avoid the endless repetition or discontinuous output
2. Don't add the system prompt, leave all prompt in the user line
   like this:

3. While evaluating the model performance, we recommend you to test several times and take the average value as the result
   Because the LLM is not stable

B. Brief introduction to the output code of DeepSeek
- When the "content" is None, the "reasoning_content" is not None
   There're two important but similar parameters in the output coding of DeepSeek: content and reasoning_content
   The former means the content of what DeepSeek is outputing, while the latter means what the DeepSeek is reasoning

   But they two never appear at the sametime, because it's the working style of R1 model

C. Brief introduction to the "Temperature"
1. The meaning of "Temperature"
   Low "temperature" means high certainty, which indicates that the percentage of model selecting the top prediction is nearly 100%
   In the contrary, high "temperature" is best suited for creative output. Because in this case the logic is not so important but the vibe
   
2. Different LLM has different temperature range
   Some ranges from 0-1, some is (0,1], while some can set the temper larger than one   

D. Follow-up question
When asking new question, DeepSeek would think over the connection between the current question and the former ones.
**It is the function that only AI can realize.**
If you search two questions sequentially in the search engineering, such as google.
You can never get the correct answer in the following way:
1st question: "What's the highest mountain"
2nd question: "What about the 2nd?"

It's the way DeepSeek realize the above function

In the follow-up question, the former answer would be added in the  content


E. The process of function calling

define the function in the tool lists, very similar to the function definition in python

The following codes are the key points of function calling


F. Vllm demo
