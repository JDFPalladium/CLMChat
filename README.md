This repository contains code for a chatbot that allows users to interact with publicly available reports and toolkits related to community-led monitoring. 

Scripts should be run in order. The first script creates descriptions of documents that are used later to create instructions for AI agents. The second script parses 
the documents themselves, creates and persists knowledge stores. The third script creates AI agents using the output of the first script, containing high-level
agents to decide which documents to explore, and document-level agents to either select specific chunks or summarize documents. The third script also sets up the
bot itself.
