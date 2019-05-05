---
layout: default
title: The Human Menu
nav_order: 3
parent: Projects
---

# Transparent Funding
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is it?

The [Human Menu](https://www.github.com/good-labs/human-menu/) project 
provides a prototype for a "human menu," or a selection of items
that contrasts the tendency to mindlessly browse social media or similar
applications. The project is inspired by the problems outlined 
by [The Center for Humane Technology](https://humanetech.com/problem/),
specifically that our attentions are captured by addictive "digital slot 
machines" to the detriment of our mental health.

## Why do we need it?

Humans use lists and suggestions to reduce cognitive load. Instead of
offering a list of YouTube videos, endlessly scrolling social media posts,
or phone apps, the Human Menu provides a selection of real world "human" options.

## Project Plan

The web interface will present a simple list of choices (5-7 that are randomly selected)
populated from an open source listing on GitHub that others can contribute to.
A user can simply select a choice, and it won't be presented again until all
choices are used up. This means the following plan of action:

 - create the GitHub repository
 - write a list of items (choices / activities to do)
 - create a web interface to display them
 - add local storage functionality
 - advanced: add keywords to filter down choices
 - test if tensorflow.js could be used to learn what a user likes.

For the first version, the list will simply be populated and the user to select,
and I'd like more advanced versions to learn over time. The application
should stay simple enough to be served from a static site with HTML and Javascript.
When it's complete, I will write a post and more widely share the idea to encourage
others to not fall victim to the economy for our attention.
