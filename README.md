[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/UpfcA4qp)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15538948&assignment_repo_type=AssignmentRepo)
# SE-Assignment-3
Assignment: Introduction to Prompt Engineering
Instructions:
Answer the following questions based on your understanding of prompt engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Definition of Prompt Engineering:
What is prompt engineering, and why is it important in the context of AI and natural language processing (NLP)?

    Prompt Engineering - any process that contributes to the development of a well-crafted prompt to generate quality, useful outputs from an AI system.
    Importance - It helps achieve desired outcomes, improves interpretability of requirements, and can mitigate biases in language models.

Components of a Prompt:
What are the essential components of a well-crafted prompt for an AI model? Provide an example of a basic prompt and explain its elements.

    Essential Components include:
    1. Clarity - clearly defining what you need
    2. Specificity - provide background information
    3. Context: provide background information
    4. Constraints - set guidelines to guide the AI's output

    Example:
    "Write a short story about a brave young girl who discovers a hidden world in her backyard."

    Elements:
    Action  - "Write" - directs the AI to perform a specific task.
    Content - "a short story" - helps narrow down the type of response
    Subject - "about a brave young girl" - provides focus to the content
    Context - "who discovers a hidden world in her backyard" - adds depth and detail to the prompt



Types of Prompts:
Describe different types of prompts (e.g., open-ended prompts, instructional prompts). How does the type of prompt influence the AI model's response?

    Types of prompts include:
    1. Classification prompts - This prompt is used to group information based on specified criteria using labels, descriptions or categories. 
    e.g "Classify the following sentence as either 'positive,' 'negative,' or 'neutral': 'I really enjoyed the movie, it was fantastic!'"

    2. Reasoning prompts - AI is prompted to draw logical conclusions and inferences about a given concept, problem or scenario.
    e.g "John is taller than Sarah. Sarah is taller than Mary. Who is the tallest among John, Sarah, and Mary?"

    3. Completion prompts - When needing to continue or expand upon an incomplete sentence, idea or problem, this type is most appropriate.
    e.g "It was a dark and stormy night. As Sarah walked down the deserted street, she suddenly heard a noise behind her. She turned around and..."

    4. Creative prompts - AI can help brainstorm or imagine new artistic or creative ideas. 
    e.g "Imagine a world where all plants glow in the dark. Describe how life would change for humans and animals in this world."

    5. Comparison prompts - The AI model can compare the attributes of different objects, concepts, products, ideas, or other variables.
    e.g "Compare the advantages and disadvantages of working from home versus working in an office."

    6. Dialogue prompts - As a writer, AI can help generate a dialogue between two characters.
    e.g "Write a conversation between a detective and a suspect, where the detective is trying to get a confession."

    7. Informational prompts - This type is similar to querying a search engine, whereby the user is seeking specific information or facts. 
    e.g "Explain how photosynthesis works in plants."

    8. Instructional prompts - This one is useful if you need to create a set of guidelines for completing a task.
    e.g "Provide step-by-step instructions on how to bake a chocolate cake from scratch."

    9. Interactive prompts - the AI model can mimic a certain personality and you can practice a dry run of your expected conversation to get the most interesting results.
    e.g AI Interviewer: "Welcome! I'm excited to learn more about you. Let's start with your background. Can you tell me a little about your experience in interior design?"

    User Input: "I’ve been studying interior design for the past two years and have worked on a few projects, mainly focused on residential spaces."

    AI Interviewer: "That sounds great! What would you say is your strongest skill in interior design—sketching concepts, material selection, or client communication?"...

    10. Summarization prompts - If you want to quickly digest a large amount of material, this one is appropriate to use. 
    e.g "Summarize the key points of the following article: 'The Benefits of Remote Work for Companies and Employees.'"

    11. Translation prompts - AI tools can be used as digital translators, translating a word, phrase, or block of text into another language.
    e.g "Translate the following English sentence into Spanish: 'The weather is beautiful today, and I'm planning to go for a walk in the park.'"

Prompt Tuning:
What is prompt tuning, and how does it differ from traditional fine-tuning methods? Provide a scenario where prompt tuning would be advantageous.

    Prompt tuning - It is a method of adapting machine learning models to perform specific tasks without retraining the model and updating its weights.

    Prompt tuning vs traditional fine-tuning methods - Prompt tuning is a variation on AI optimization that modifies the input prompt to guide the model’s output without retraining for data12345. It is ideal for quickly adapting a model to various tasks with minimal resources. Fine-tuning, on the other hand, involves retraining the model on a specialized dataset to adapt responses to specific contexts or domains.

    There are a number of scenarios in which prompt engineering would be advantageous. Here are a few:

        Specific User Interaction Styles - If you're designing a virtual assistant that interacts with users in a specific tone (e.g., formal or humorous), prompt tuning can help adjust the assistant's responses to match the desired interaction style without altering the underlying model.


Role of Context in Prompts:
Explain the role of context in designing effective prompts. How can adding or omitting context affect the output of an AI model?
    
    Context in AI refers to the surrounding information and circumstances that influence how a prompt is interpreted and responded to. If you’re discussing a technical subject, including specific terms or details helps the AI grasp the context better, enhancing the quality of its output.
    Moreover, context encompasses the user’s goals and experiences. If you provide background information, the AI can tailor its responses to suit your needs more effectively. Keeping context in mind not only improves communication with AI but also enhances the overall user experience.
    
    Without proper context, the AI might misinterpret your intent, leading to answers that don’t align with your needs. For instance, when you ask a question, the AI considers previous interactions, the specific wording of your prompt, and the broader topic at hand. This means that even slight variations in phrasing can yield different results.


Ethical Considerations in Prompt Engineering:
What ethical issues should be considered when designing prompts for AI systems? Discuss potential biases and how they can be mitigated.
    Ethical issues:
    1. Technological singularity 
    2.AI impact on jobs 
    3. Privacy
    4. Bias and discrimination 
    5. Accountability

    Biases and how to mitigate them:
    Potential biases in prompt engineering can include gender, cultural and racial biases. Consider the following prompt and response for example:

        Prompt: Tell a story about a nurse

        Response:  In the bustling halls of St. Mary’s Hospital, nurse Emily moved with purpose. Her gentle demeanor and unwavering dedication were the beacon of hope for patients and colleagues alike. Every day, she donned her scrubs like armor, ready to battle illness and despair with compassion and skill.

        One stormy night, a young boy named Jacob was admitted, his face etched with fear. Emily sat by his side, soothing his worries with tales of bravery and resilience. Through her care, Jacob found solace, and in her kindness, he found courage. In nurse Emily’s embrace, healing began, one heartbeat at a time.
    
    The model described the nurse as a female, reflecting stereotypes about gender roles in nursing.
    Biases can be mitigated by the following approaches:
    a. Ethically-informed prompts reduced biased output and had more equitable representation of diverse demographic groups than neutral prompts.
    b. Context: Specific prompt designs, with emphasis on inclusive language, social context can enhance fairness in numerous applications. 

    Here's a prompt and response example, applying the above mitigations:
        Prompt: Write a story about a nurse, ensuring gender-neutral language and equitable representation of different ethnic backgrounds

        Response:In a bustling hospital, Alex, a compassionate nurse, navigated the corridors with grace. They comforted patients with diverse backgrounds, from Maria, a Spanish-speaking elder, to Malik, a young refugee. Alex’s gentle touch and empathetic words transcended language barriers, offering solace to all. Their dedication knew no bounds, attending to every soul with equal care. Amidst the chaos, Alex’s presence radiated warmth, embodying the unity of humanity in the healing embrace of healthcare.


Evaluation of Prompts:
How can the effectiveness of a prompt be evaluated? Describe some metrics or methods used to assess prompt performance.

    Effectiveness of prompts is evaluated using metrics. Below are some metrics commonly used:
        a. Output Quality
            - Human Evaluation - Humans read and rate output
            - Automated Metrics - e.g BLEU & ROUGUE which compare your output to an ideal output and score it based on how closely it matches
            - Domain-Specific Metrics
        b. Divesity 
            - Entropy - a measure of how unpredictable a system is. In the context of language models, it can tell you how evenly your model is distributing its probability mass across different outputs. 
            - Cosine Similarity - calculated to see how similar your outputs are. If they are similar, the cosine similarity score will be high.
            - N-gram Overlap - You can calcualte the overlap between the n-grams (sequence of n words) in your outputs to get a sense of their similarity. 
        c. Speed 
            Time how long it takes your prompts to generate output. This metric will be affected by size and complexity of models, as well as hardware limitations
        d. Consistency 
            Generate output from the same prompt multiple times and compare the results. If they're very different from each other, your model is not consistent.

Challenges in Prompt Engineering:
Identify and discuss common challenges faced in prompt engineering. How can these challenges be addressed?
    1. Vague Instructions - When prompts lack specificity, the AI may produce content that is too broad or not aligned with your expectations. To avoid this, be as specific as possible in your prompts.
    2. Lack of context - Without context, the content of the AI response may lack coherence and relevance. Providing details and background information can ensure the response aligns with your objectives.
    3. Overcomplicated prompts - The AI may struggle to understand and respond effectively to prompts that are too complex. Breaking down complex instructions into simpler, more manageable parts.
    4. Ignoring AI capabilities and limitations - This can lead to frustration and subpar results. By setting realistic expectations and leveraging the AI'S strenghts, you can optimize your content creation process and achieve better results. 
    5. Inconsistent Prompting - This can lead to varied and unpredictable AI responses. Practicing consistent prompting helps the AI learn your preferences and produce more reliable content over time. 


Case Studies of Prompt Engineering:
Provide an example of a successful application of prompt engineering in a real-world scenario. What were the key factors that contributed to its success?
    Text Generation: OpenAI Chat GPT
    The ability to generate high-quality text has numerous applications, ranging from writing emails and blog posts to summarizing complex information and answering questions. Chat GPT has demonstrated remarkable capabilities in this domain. 
    Factors that have contributed to the success of text generation include:
        1. Pretraining
        2. Fine-tuning
        3. Zero-shot learning
        4. Interactiveness


Future Trends in Prompt Engineering:
What are some emerging trends and future directions in the field of prompt engineering? How might these trends shape the development of AI and NLP technologies?
    Emerging trends include:
        1. Multimodal AI (and video) - The incoming generation of interdisciplinary models, comprising proprietary models like OpenAI’s GPT-4V or Google’s Gemini, as well as open source models like LLaVa, Adept or Qwen-VL, can move freely between natural language processing (NLP) and computer vision tasks. AI will become more intuitive and versatile. Moreover, multimodal AI allows for a model to process more diverse data inputs, enriching and expanding the information available for training and inference.
        2. Smaller language models and open source advancements - They are far less resource-intensive. Training smaller models on more data yields better performance than training larger models on fewer data.Smaller models will make AI more explainable, will help democratize AI and be run locally on smaller devices.
        3. Customized local models and data pipelines -With the right data and development framework, existing open source AI models and tools can be tailored to almost any real-world scenario, from customer support uses to supply chain management to complex document analysis. Keeping AI training, inference and retrieval augmented generation (RAG) local avoids the risk of proprietary data or sensitive personal information being used to train closed-source models or otherwise pass through the hands of third parties.

References: 
https://promptengineering.org/what-is-prompt-engineering/
https://www.geeksforgeeks.org/what-is-prompt-engineering-the-ai-revolution/
https://medium.com/@oril_/prompt-engineering-in-ai-and-its-practical-applications-d7dffef77f96
https://www.grammarly.com/blog/generative-ai-prompts/?msockid=316809d9d060640d346b1d71d16065ef
https://research.ibm.com/blog/what-is-ai-prompt-tuning
https://medium.com/@pvsravanth/prompt-tuning-vs-fine-tuning-whats-the-difference-27dadbe982c6
https://saasprompts.com/the-importance-of-context-in-ai-prompting/#:~:text=The%20Importance%20of%20Context%20in%20AI%20Prompting%201,Contextual%20AI%20...%207%20To%20Wrap%20Up%20
https://venturebeat.com/ai/mitigating-ai-bias-with-prompt-engineering-putting-gpt-to-the-test/
https://learnpromptengineering.dev/article/How_to_evaluate_the_effectiveness_of_your_prompts.html
https://onverb.com/common-pitfalls-in-prompt-engineering-and-how-to-avoid-them/
https://medium.com/kinomoto-mag/case-studies-in-prompt-engineering-real-world-applications-and-insights-d1ec4ffc421a

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
