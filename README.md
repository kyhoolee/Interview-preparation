## Coding preparation 
### Target 
* Coding prepration 
* Two type of interview
  - Coding on online-editor like hackerrank
  - Human-interview: receive problem - explain idea - coding on online text-editor (No coding support)
* Require
  - Understanding and able to demonstrate the algorithm step-by-step
  - Quick solving problem: realize situation - quick solution idea - quick improving idea - evaluate quality of solution

### Detail 
* Finish review famous algorithm: 
  - from basic sorting to basic graph algorithm
  - No need to review hard-algorithms
  - Link: [Algorithm](https://www.hackerearth.com/practice/algorithms/searching/linear-search/tutorial/)
* Practice:
  - Focus on Easy and Medium problem
  - No need to solving hard-problem
  - Link: [Practice](https://www.hackerrank.com/domains/tutorials/cracking-the-coding-interview)
  
## System design prepration
### Target
* System design prepration
  - Understanding basic principle of design system
  - Important properties to consider when designing a system
  - Explain properties of famous existing system

* Practice:
  - Review these resource links below. Read it and demonstrate problem and solution to others
  - Summary the general steps to design the solution to common problems
### Reference
* [English version](https://github.com/donnemartin/system-design-primer)
* [Vietnamese version](https://github.com/nesso99/system-design-beginner)

### Sample interview question
* [Good sample](https://hackernoon.com/top-10-system-design-interview-questions-for-software-engineers-8561290f0444)
* Focus on design Data ETL Pipeline question

### Sample tool question 
* Distributed storage system Hadoop file
  - Sendo and VCC both using Hadoop
  - Describe basic of Distributed file system: Name node, data node, basic function, how to divide big file into small part across machine, how basic operation of file happen, ...
* Distributed search engine Elasticsearch
  - Search engine is important part at Sendo
  - Describe basic principle of Indexing and Searching
  - Describe how Elasticsearch handle data distributedly

* Distributed computing system: Hadoop Map-reduce, Spark
  - Describe basic principle of Map-reduce
  - How Spark speed up MapReduce task computing
* Realtime queue: Kafka, Redis pubsub, ...
  - Basic principle of Event queue
  - Describe some use-case of queue 
* Logging system: Fluentd, Logstash, ...
  - Log collector is a common module in every data mining system - Connecting log source and log destination
  - Describe basic logic of an logging system - Fluentd or Logstash
* Caching database: Redis  
  - How to cache model result
  - Basic usage of Redis
* Design system: Log collector --> raw data storage --> Batch processing --> Event realtime processing --> Caching --> Service  
  - Design realtime system: Twiter feeds, Facebook feeds, ...
  


