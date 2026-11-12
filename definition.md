- AI is a science of making machines perform tasks that normally requires human intelligence
- Machine learning is when machine learns from lots and lots of example sets
- Transformers concept and Attention is all you need (2017)
- LLMs(Large language models)- transformers trained on very large data
- Generative AI - Generate content (multi modal - text, image, video)
- Search engine - Retrieve info; LLMs - Generate response
- Search engine vs LLMs-
- Google: Question -> search an index -> rank relevant documents -> return results; //Crawlers/Spiders checks the internet always and rank the index
- ChatGPT - Prompt -> Learnt Patterns -> Predicts next text -> generate response

- What knowledge does LLM contains - A trained Neural Network contains a very large collection of numbers called parameters or weights. During training, these numbers are repeatedly adjusted.

- Base model - It is a model trained to predict next token or text
- AI Assistant - Base Model + web search + Files + instruction tuning + human feedbacks + memory + retrieval + tool access + system instructions + safety training + content filters + conversation management + guard rail + security + auth
- Inference (vs Training) - The process of giving the information back after prompt is inference.
- Hallucination - A hallucination occurs when an AI model generates information that appears plausible, but is unsupported, incorrect, misleading or fabricated.
- RAG - Retrieval Augmented Generation - generate based on specific data retrieval - LLMs + extra private info
- Sub word tokenization - word tokenization creates a very lengthy vocabulary; character tokenization creates a very long sequences; subword is a balance of both
- Vocabulary and Token Id - The vocabulary is the collection of tokens that the tokenizer knows how to represent directly. Ex - 
Token - "the", "is", "Java", "script", ".", "ing".
Id - 10, 11, 12, 13, 14, 15
- Byte Pair Encoding - BPE builds a vocabulary by repeatedly merging frequently occuring neighbouring pieces.
- Context window - A context window is the amount of tokenised information a model can process within a request or active generation context. A language model does not have unlimited working memory, every model has a limit on how many tokens it can process at once. This is called context window. 
- Context may include - system instructions, current prompt, previous messages, uploaded document context, retrieved information, tool outputs, the model's generated response. All of these consume tokens.
- What happens when context window fills - Different applications may handle this differently - 
- possible strategies include - removing older conversations, summarising previous messages, retrieving only relevant sections, splitting the work into multiple requests
- visible conversation in the chat interface and the exact text in the model's context are not always identical. Every model has maximum context length.
- Vectorisation - vectorisation is the process of converting information(text, images, users, product or any information) into numerical vectors(array of numbers) Ex - [2,5], [3,8,7], [0.12, -3.5, 4.29] etc
-- It turns information into a form on which computers can perform mathematical operations.
- Embedding - An embedding is a learned numerical representation of an item that captures useful relationships with other items
  
