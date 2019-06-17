---
redirect_from:
  - "/guide/01-overview"
title: 'Getting started'
prev_page:
  url: /intro
  title: 'Home'
next_page:
  url: /guide/02_create
  title: 'Create your book'
comment: "***PROGRAMMATICALLY GENERATED, DO NOT EDIT. SEE ORIGINAL FILES IN /content***"
---
# The Jupyter Book Guide

This is a guide for creating your own book using
Jupyter Notebooks and Jekyll. Book content is written in markdown and
Jupyter Notebooks, and `jupyter-book` converts these into
a book fit for hosting on the web.

## Install the command-line interface

First off, make sure you have the CLI installed so that you can work with Jupyter Book.
The Jupyter-Book CLI allows you to create, build, upgrade, and otherwise control your
Jupyter Book. You can install it via pip with the following command:

```
pip install jupyter-book
```

## A quick tour of a Jupyter Book

Jupyter-Book comes with a demo book so that you can see how the content files
are used in the book. We'll begin with a quick tour of these files, as they are
the pieces that you'll modify for your own book.

To create a **demo Jupyter Book** to use as a template, run the following command:

```
jupyter-book create mybookname --demo
```

A new book will be created at the path that you've given (in this case, `mybookname/`).

Let's take a quick look at some important files in the demo book you created:

```
mybookname/
