# Milvus — Database Developer

[← back to Milvus](README.md)

| Question | Difficulty | Seniority | Tool / Technology | Interview Round | Question Bank | Open in Locus |
|---|---|---|---|---|---|---|
| A team wants Pinecone for RAG vector search; another wants pgvector on the existing Postgres they already operate — adjudicate build-vs-buy at your scale considering recall, index-rebuild cost, per-query economics, and one-more-datastore operational tax. | deep understanding | SDE-2/3, Architect/Principal | Build vs Buy Decisions | Onsite, Hiring Manager | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=a-team-wants-pinecone-for-rag-vector-search-another-wants-pgvector-on--112959) |
| How would you architect caching for embeddings and vector-search results backed by a vector database so an index rebuild invalidates the affected cached neighborhoods without a global flush on every rebuild? | deep understanding | SDE-2/3, Architect/Principal | Caching | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=how-would-you-architect-caching-for-embeddings-and-vector-search-resul-111517) |
| Explain how you'd shard a vector-search index of 500M embeddings across nodes for a retrieval service, how you route a query and merge top-k across shards, and the recall-versus-latency trade-off of the scatter-gather fan-out. Where does a hot shard hurt tail latency? | deep understanding | SDE-2/3, Architect/Principal | Distributed Systems | Phone Screen, Onsite | Tech | [Open](https://skillmeet.ai/?tab=locus&view=questions&slug=explain-how-you-d-shard-a-vector-search-index-of-500m-embeddings-acros-112122) |
