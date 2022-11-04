---
title: 'Configure'
teaching: 10
exercises: 2
---


:::::::::::::::::::::::::::::::::::::: questions 

- How do I configure my Reader's environment


::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- To learn how to define the location of your data sets and helper files

::::::::::::::::::::::::::::::::::::::::::::::::

## Your local library

The Distant Reader is modeled on a library. Distant Reader data sets are called "study carrels", and collections of study carrels are called a "library". My default, your collection of study carrels is saved in your home folder/directory in a folder/directory named "reader-library". You can configure the location of the library using the `rdr set` command. Configure its location now, and accept the defaults:

  * `rdr set -s local`

You can confirm the location using the `rdr get` command. Confirm the good work you just did:

  * `rdr get -s local`
  
The Reader uses a few other applications to perform certain functions, most importantly MALLET, and Apache Tika. Set and get their configurations, and again, for right now, accept their defaults:

  * `rdr set -s mallet`
  * `rdr set -s tika`
  * `rdr set -s notebooks`
  
  * `rdr get -s mallet`
  * `rdr get -s tika`
  * `rdr get -s notebooks`
  

::::::::::::::::::::::::::::::::::::: keypoints 

- The Reader needs to know where your data resides

- The Reader needs to know where helper files and applications reside

::::::::::::::::::::::::::::::::::::::::::::::::

