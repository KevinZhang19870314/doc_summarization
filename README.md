# Document Summarization

This plugin hooks into the `BlackHole` to ask the Language Model to summarize groups of text chunks. 
Summaries are stored in the vector memory, along with the original chunks.  

The summarization can help the Deep AI to have a more comprehensive understanding of the content of the documents.

> **Warning**
> The summarization increases considerably the uploading time if the document size is big.  
> Moreover, when this plugin is enabled the Deep AI makes and additional call to the language model API.
