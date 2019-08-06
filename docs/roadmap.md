---
layout: default
title: Roadmap
nav_order: 30
---

# Roadmap of Dejournal

## Platform prototype (July 2019)
The platform currently runs on Rinkeby testnet. It allows three main features: 
* Publishing of papers
* Querying papers by ID number
* Listing last 5 publications

Listing of all submissions is not implemented through the web application due to a large amount of data that needs to be processed. This can be done by directly querying the smart contract.

Searching is not available due to the limitations of the smart contracts on Ethereum blockchain. A separate indexing and search engine platform will be implemented to solve this.

## Indexing and search engine (Jan 2020)
This will be a centralized application that will index all the papers on Dejournal. It will allow searching by keywords. You can think of it as Google for Dejournal.

## Peer review module (July 2020)
The central part of scientific publishing is peer review. It is a quality control system that helps maintain high quality of papers. Currently this is done by individual journals and is a closed process. Only few journals publish reviews publicly.

Dejournal will implement an open peer review system. The DAO will define the rules to qualify the reviewers. An author of a paper could also pay a reward for reviewers at the time of submission and define how to split it.

## Data replication system
In theory, anyone could find the hashes of all Dejournal files stored on IPFS and replicate them. We want to simplify this by making data replication straight-forward and simple.

The next step is to set up a rewards system for nodes that register as data replicators. 