# SystemDesignArchitecture-Interview

# Distributed Locks -Tech Dummies
# Distributed Systems -Horizontal & Vertical Scaling
# Distributed Data Stores & works
# Transactions Internal Implementation write a head log and locks with banking.
# What is pessimistic and optimistic locking
# How Google searches one document among Billions of documents quickly?
# Stream processing :System design basics: Real-time data processing
# When to use distributed computing | how distributed computing works (Big problem |computation)
# Learn about Distributed file systems
# System design basics:
# What is asynchronous processing?
# Infrastructure as code introduction
# Data corruption and Merkle trees
# In Memory databases internals for system design interviews (Real-time Databases) :indexing ,AVL Tree
# How row oriented and column oriented db works?
# Bit Map:EFFICIENT COUNTING USING BITMAPS FOR SYSTEM DESIGN
# LEARN BITMAP INDEXES:BitMap Indexing 
# Clustered vs UnClustered index Structures
# Distributed Cache:
# Bloom Filter
# Solve boggle
# egg solver
# Amazon interview question: Implement FloodFill algorithm
# Sketches
# Count min sketch | Efficient algorithm for counting stream of data | system design components
# Hyperloglog: Facebook's algorithm to count distinct elements
# Reducing N/W Calls
# Search Engine Indexing & Data Structures
# Hash Consistent-Hash Ring
# https://gist.github.com/VarunVats9/9e80836f634b42c437436666d6a74007
# Book :Orielly#Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems Kindle Edition ##

**Search engine indexing and data structures**: are fundamental components of search engines that enable efficient and quick retrieval of relevant information from vast amounts of data available on the web. Let's explore these concepts:

Search Engine Indexing:
Definition: Search engine indexing is the process of collecting, parsing, and storing data from web pages to facilitate fast and accurate information retrieval during user searches.

Crawling: Search engines use web crawlers (also known as spiders or bots) to navigate the web and discover new or updated content. These crawlers follow links from one page to another, collecting information along the way.

Parsing and Analysis: The content of web pages is then parsed and analyzed to extract relevant information, including text content, metadata, and links. This process involves removing HTML tags, identifying keywords, and creating a structured representation of the content.

Document Representation: Each web page is represented as a document, and the collected information is stored in an index. The index contains a mapping between terms (keywords) and the documents that contain them.

Inverted Index: Search engines typically use an inverted index data structure. In an inverted index, terms are mapped to the documents that contain them, allowing for quick retrieval of documents containing specific terms.

**Data Structures Used in Search Engines:**
Inverted Index:

Posting Lists: Each term in the index has an associated posting list that contains references (pointers or document IDs) to the documents where the term appears.
**Term Frequency (TF):** Indicates how often a term appears in a document.
**Inverse Document Frequency (IDF):** Measures the importance of a term across all documents.
PageRank Algorithm:

Graph Representation: The web can be represented as a graph, where web pages are nodes and hyperlinks are edges.
PageRank Score: Assigns a numerical score to each page based on the number and quality of links pointing to it. Pages with higher scores are considered more authoritative.
Trie (for Autocomplete):

Prefix Tree: Used for implementing autocomplete suggestions. It stores a dynamic set of strings in a tree structure, and common prefixes are shared among related strings.
B-trees and Tries (for Databases):

B-trees: Often used in database indexing to efficiently organize and retrieve data on disk.
Tries: Trie data structures are used in databases and search engines for storing and searching key-value pairs.
Hash Tables:

**URL Hashing:** Search engines may use hash tables for quick lookups of URLs and associated metadata.
**Machine Learning Models:**

**Ranking Algorithms:** Search engines often use machine learning models to improve search result rankings based on user behavior, relevance, and other factors.
Understanding and optimizing these data structures is crucial for search engines to provide users with relevant and timely search results efficiently. Search engines continually evolve and incorporate new technologies to enhance their indexing and retrieval capabilities.


