---
layout: archive
title: ""
permalink: /chat/
author_profile: true
---


<div style="position: relative; padding-bottom: 75%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe 
    src="https://debetten-debottencourt.hf.space" 
    frameborder="0" 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture">
  </iframe>
</div>

---

## About

de-Bot-tencourt is an AI-powered chatbot trained on my research publications and personal website. You can ask it questions about my work, including attention and memory dynamics, AI-driven mental health interventions, real-time neurofeedback and neuroadaptive systems. 

Note: that I am logging these interactions to assess and improve performance! 
Therefore, please avoid sharing personal or sensitive information. 

## How it works

This chatbot uses a RAG (Retrieval-Augmented Generation) pipeline, powered by Mistral's LLM, and is deployed on Hugging Face Spaces.

I drew inspiration from a few different guides and resources:
- [LangChain's RAG Tutorials](https://python.langchain.com/docs/tutorials/rag/)  
- [Blogposts](https://medium.com/credera-engineering/build-a-simple-rag-chatbot-with-langchain-b96b233e1b2a)
- [ChangHoon Han's ChangBot](https://changhoonhahn.github.io/) (the original inspiration)

I extended these approaches by: 
- Indexing PDFs of my research publications (most tutorials scraped the web or arxiv publications)
- Resolving versioning issues
- Integrated the Google Sheets & Drive API for real-time logging of user questions and chatbot responses


## Note

This chatbot is very preliminary, if you actually want to chat with me (and not the bot version of me), feel free to reach out!