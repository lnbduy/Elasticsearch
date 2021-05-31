# Overview
  Elasticsearch is a real-time, distributed storage, search, and analytics engine. 
  It can be used for many purposes, but one context where it excels is indexing streams of semi-structured data, such as logs or decoded network packets
  ## ElasticSearch origins
  - Lucene (99) -> Compass (04) -> ElasticSearch (10)
  ## Elastic Stack overview
  - LogStash/Beats -> Elastic Search -> Kibana
  - Add-On: A-Pack
  - Scalability
  - Near Real-Time
  - Schemaless
  - Advanced Query Language
  ## Use cases
  - Security/Log analytics
  - Marketing
  - Operations
  - Search
  ## Concepts
  - Cluster
  - Node
  - Index (collection of similar document)
  - Type (inside index - cateogry or partition of index)
  - Document (base unit : single customer/order)
  - Shard/Replica
    - Index to be scalable. 
    - Replica is a segment of index
    - Shard is a portion of index
    - Default 5 shard, 1 replica
    - Cluser -> Multi node. Each node -> Index (primary) -> Types -> Document
# Setup
 Website https://www.elastic.co/
 ## Running ElasticSearch in the cloud
 ## Install ElasticSearch locally
