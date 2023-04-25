# sensical

**Find and manage duplicates in a large collection of files across several storage devices**

# Motivation
This program solves a personal need. If you have files copied from one computer to the next, CDs DVDs, and Hard disks full of your
old work, it becomes hard to know what you have. Multiple copies of the same thing, sometimes with additions or changes.

Sensical will build a database of all the devices or directories you feed it, and show you the duplicates. It will even help you 

# Design
  ## Database
  sqlite3
  * well integrated into python
  * disk-based as well as memory based (anticipte the database will be large and would be nice to avoid rescan each time)
  * SQL syntax

  ## Tables
  * Sources
  * Files

  ## Hashing
  

# Project Status
* Proposal 2023/4/23 creation and initial README
* Plan
  * Python for programming language (lots of mature modules)
  * sqlite3 for the database
  * python hashlib for making hashs of file contents (blake2s looks like a good choice)
  * not sure of presentation gui -- tkinter might be easiest and most transportable

