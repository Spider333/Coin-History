# Blockchain Reading List

This is a list of readings (and watchings) on **blockchain** related topics.


## Preamble

The word _"blockchain"_ (or _"block chain"_) started off as a more or less narrowly defined technical term.

It (_"blockchain"_) later became a buzzword that represented anything related to BitCoin, alt-coins (ex: LiteCoin, Ethereum, etc), cryptocurrencies, etc.

And now that the word _"blockchain"_ is on the verge of becoming a _household name_,
it seems like it is starting to include what some others are calling _"distributed computing"_.

(In some usages of the label _"blockchain"_, neither _blocks_ or _hash lists_ seemed to be necessary for that thing to be called a _"blockchain"_.)

This seems to somewhat mirror how previously the usage of the word _"P2P"_ seemed to broaden and also include what others are calling  _"distributed computing"_.

(Although this time around, cryptography and various concepts of "money" seems to have prominence.)

Regardless, this document focuses on a more traditional definite of _"blockchain"_.


## Audience

This document is targeted at technical people, who are looking to gain a deep understand of the concepts behind blockchain based technologies.

But also includes some topics that the author of this document feels that, while not strictly about blockchains,
will help provide you with a deep(er) technical background that can be useful when working with blockchain technologies.


## Topics
* [BitCoin](#bitcoin)
* [Bit Gold](#bit-gold)
* [Consensus](#consensus)
* [Cryptography](#cryptography)
* [Distributed Computing](#distributed-computing)
* [Distributed Hash Tables](#distributed-hash-tables)
* [Handicap Principle](#handicap-principle)
* [Hashcash](#hashcash)
* [Hash Lists](#hash-lists)
* [Identity](#identity)
* [Money](#money)
* [Peer-to-Peer Networks](#peer-to-peer-networks)
* [Raft](#raft)
* [Smart Contracts](#smart-contracts)


## BitCoin

* [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf),
  by Satoshi Nakamoto


## Bit Gold

* [Bit gold](https://unenumerated.blogspot.com/2005/12/bit-gold.html),
  by Nick Szabo


## Consensus

* See also: [BitCoin](#bitcoin), [Raft](#raft)


## Cryptography

* [Communication Theory of Secrecy Systems](http://netlab.cs.ucla.edu/wiki/files/shannon1949.pdf),
  by Claude Elwood Shannon

* [New Directions in Cryptography](http://wwwknoll.in.tum.de/pub/Main/TeachingSs2006EinfuehrungInformatik2/diffie.pdf),
  by Whitfield Diffie, Martin E. Hellman

* [A Method for Obtaining Digital Signatures and Public-Key Cryptosystems](https://people.csail.mit.edu/rivest/Rsapaper.pdf),
  by Ronald Linn Rivest, Adi Shamir, Leonard Adleman

* [How RSA Works With Examples](http://doctrina.org/How-RSA-Works-With-Examples.html),
  by Barry Steyn

* [Why RSA Works: Three Fundamental Questions Answered](http://doctrina.org/Why-RSA-Works-Three-Fundamental-Questions-Answered.html),
  by Barry Steyn

* [Cryptographic Hash VS MAC: What You Need To Know](http://doctrina.org/Cryptographic-Hash-Vs-MAC:What-You-Need-To-Know.html),
  by Barry Steyn


## Distributed Computing

* [Introduction to Distributed System Design](http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html),
  by _"unknown"_

* [Perspectives on the CAP Theorem](http://groups.csail.mit.edu/tds/papers/Gilbert/Brewer2.pdf),
  by Seth Gilbert, Nancy A. Lynch

* [The Log: What every software engineer should know about real-time data's unifying abstraction](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying),
  by Jay Kreps

* [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/),
  by Jeff Hodges

* [Immutability Changes Everything (video)](https://vimeo.com/52831373),
  by Pat Helland

* [Immutability Changes Everything (paper)](http://cidrdb.org/cidr2015/Papers/CIDR15_Paper16.pdf),
  by Pat Helland

* [Kafka: a Distributed Messaging System for Log Processing](http://notes.stephenholiday.com/Kafka.pdf),
  by Jay Kreps, Neha Narkhede, Jun Rao

* [Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications](https://pdos.csail.mit.edu/papers/chord:sigcomm01/chord_sigcomm.pdf),
  by Ion Stoica, Robert Morris, David Karger, M. Frans Kaashoek, Hari Balakrishnan

* [Dynamo: Amazon’s Highly Available Key-value Store ](http://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf),
  by Giuseppe DeCandia, Deniz Hastorun, Madan Jampani, Gunavardhan Kakulapati, Avinash Lakshman, Alex Pilchin, Swaminathan Sivasubramanian, Peter Vosshall, Werner Vogels

* [MapReduce: Simplified Data Processing on Large Clusters](https://research.google.com/archive/mapreduce.html),
  by Jeffrey Dean, Sanjay Ghemawat

* [The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby.html),
  by Mike Burrows

* [So, you want to trace your distributed system? Key design insights from years of practical experience](http://www.pdl.cmu.edu/PDL-FTP/SelfStar/CMU-PDL-14-102.pdf)
  by Raja R. Sambasivan, Rodrigo Fonseca, Ilari Shafer, Gregory R. Ganger

* [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](https://research.google.com/pubs/pub36356.html),
  by Benjamin H. Sigelman, Luiz André Barroso, Mike Burrows, Pat Stephenson, Manoj Plakal, Donald Beaver, Saul Jaspan, Chandan Shanbhag

* See also: [Consensus](#consensus), [Peer-to-Peer Networks](#peer-to-peer-networks)


## Distributed Hash Tables

* [Kademlia: A Peer-to-peer Information System Based on the XOR Metric](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf),
  by Petar Maymounkov, David Mazières


## Handicap Principle

* [The Handicap Principle: A Missing Piece of Darwin's Puzzle](http://www.goodreads.com/book/show/885547.The_Handicap_Principle),
  by Amotz Zahavi, Avishag Zahavi


## Hashcash

* [Hashcash - A Denial of Service Counter-Measure](http://www.hashcash.org/papers/hashcash.pdf),
  by Adam Back


## Hash Lists

* [How to Time-Stamp a Digital Document](https://link.springer.com/chapter/10.1007/3-540-38424-3_32),
  by Stuart Haber, W. Scott Stornetta


## Identity

* [Identity Crisis: How Identification Is Overused and Misunderstood](https://www.goodreads.com/book/show/171237.Identity_Crisis),
  by Jim Harper

* [Secrets and Lies: Digital Security in a Networked World](https://www.goodreads.com/book/show/304482.Secrets_and_Lies),
  by Bruce Schneier

* [Secure Electronic Commerce: Building the Infrastructure for Digital Signatures and Encryption](https://www.goodreads.com/book/show/1174424.Secure_Electronic_Commerce),
  by Warwick Ford, Michael S. Baum

* [Understanding Windows CardSpace: An Introduction to the Concepts and Challenges of Digital Identities ](https://www.goodreads.com/book/show/22380161-understanding-windows-cardspace),
  by Vittorio Bertocci, Garrett Serack, Caleb Baker

* [7 Laws of Identity](https://web.archive.org/web/20090824224507/https://www.identityblog.com/?p=1065)
  by Kim Camerons,

* [Getting Started with OAuth 2.0](https://www.goodreads.com/book/show/13228633-getting-started-with-oauth-2-0),
  by Ryan Boyd

* [Digital Identity](https://www.goodreads.com/book/show/155374.Digital_Identity),
  by Phillip J. Windley

* [Identity Management: A Primer](https://www.goodreads.com/book/show/7273193-identity-management),
  by Graham Williamson, David Yip, Ilan Sharoni, Kent Spaulding


## Money

* [Shelling Out: The Origins of Money](http://nakamotoinstitute.org/shelling-out/),
  by Nick Szabo


## Peer-to-Peer Networks

* [Understanding Churn in Peer-to-Peer Networks](http://www.barsoom.org/papers/imc-2006-churn.pdf),
  by Daniel Stutzbach, Reza Rejaie

* See also: [BitCoin](#bitcoin), [Bit Gold](#bit-gold), [Distributed Hash Tables](#distributed-hash-tables)


## Raft

* [The Raft Consensus Algorithm](https://raft.github.io/),
  by Diego Ongaro, Et al.

* [Raft: Understandable Distributed Consensus](http://thesecretlivesofdata.com/raft/),
  by Ben Johnson

* [In Search of an Understandable Consensus Algorithm (Extended Version)](https://raft.github.io/raft.pdf),
  by Diego Ongaro, John Ousterhout


## Smart Contracts

* [The Idea of Smart Contracts](http://www.fon.hum.uva.nl/rob/Courses/InformationInSpeech/CDROM/Literature/LOTwinterschool2006/szabo.best.vwh.net/idea.html),
  by Nick Szabo
