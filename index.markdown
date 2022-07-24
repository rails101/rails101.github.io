---
layout: default
title:  "Rails 101"
---

# Welcome

This guide represents an accumulation of knowledge and best practices that I have developed over years of working with Ruby on Rails and, more recently, combining it with GraphQL to build powerful APIs. I wrote this for you and I hope you enjoy it.

## Chapters

{% assign posts = site.posts | sort:"date" %}
{% for post in posts %}
  1. [{{ post.title }}]({{ post.url }})
{% endfor %}

* * *

## Questions

### Who should read this guide?

This guide is for anyone new to [Ruby on Rails](https://rubyonrails.org/) or [GraphQL Ruby](https://graphql-ruby.org/), anyone looking for a refresher, or anyone that's interested in modern best practices.

### What is in this guide?

The contents of this guide aim to give the reader a basic understanding of [Ruby on Rails](https://rubyonrails.org/) and how it, combined with several other technologies like [GraphQL](https://graphql.org/) and [PostgreSQL](https://www.postgresql.org/), can be used to build a **stable** and **scalable** backend.

### What about the client side?

Building a front end is outside the scope of this guide, but there will soon be a React project that you can follow along with.

### How long should this guide take?

You should be able to read and work through this guide in 1-2 days.

### What are the core technologies covered?

* Ruby on Rails
* GraphQL
* PostgreSQL
