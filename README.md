## Description
Architecture.md presents an overview of the general architecture for a knowledge base creator app I developed for our AI integrations team, to facilitate effective knowledge base creation from un-chunked docs. 
3 chunking strategies are used to create 3 temporary knowledge versions, which are scored using Ragas, and the most effective strategy is selected as the final product, which is upserted to pinecone.

I was tasked with researching the best tools for achieving this, planning and building the prototype. 
After a few iterations the prototype was approved by our product manager, and I collaborated with a senior engineer to expand the design to a robust web app. 
It's currently used as part of our company's internal AI tools. 
