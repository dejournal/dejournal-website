---
layout: default
title: Structure
nav_order: 20
---

# Structure of the platform

## IPFS node
Each submission on Dejournal generates two files that are stored on IPFS nodes. 

The first file that is uploaded is the file containing the manuscript, usually a PDF. The IPFS identifier of this file is then returned to the Dejournal app and stored in a metadata JSON text file. Besides the manuscript file identifier, this JSON contains also data, such as title, authors and abstract. This is the second file that is uploaded to the IPFS node and the identifier of this file is then stored on Ethereum blockchain.

## Smart contract
The Dejournal smart contract stores the IPFS identifiers of JSON files with metadata and manuscript IPFS identifiers. Besides the identifier it also stores the public key of the wallet that submitted the paper and a timestamp. 

The smart contract is developed with Truffle framework.

## Web application
The user interface of Dejournal is a Web application binding together all of these parts. Here are some basic information about the app:

* Programming language: JavaScript
* Framework: ReactJS
* UI library: Bootstrap 4
* Ethereum blockchain library: web3.js
* IPFS library: ipfs-mini.js