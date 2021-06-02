---
marp: true
theme: gaia
size: 4K
class: default
paginate: true
footer: '![](images/twitter_24.png) [asm0di0](https://twitter.com/asm0di0)'
backgroundImage: "linear-gradient(to bottom, #000 0%, #1a2028 50%, #293845 100%)"
color: white
title: Noname
---
<!--
_class: lead
_paginate: false
_footer: ""
-->

<style>
footer {
    display: table
}
.hljs-variable { color: lightblue }
.hljs-string { color: lightgreen }
.hljs-params { color: lightpink }
</style>

# Spark for Java Devs

Pasha Finkelshteyn, JetBrains

---

![bg right:40%](images/avatar.jpg)

# Who am I

- ex system administrator
- ex developer
- ex team lead
- ex data egineer
- developer advocate for big data

Together >14 years in IT

---

# Who are data engineers?

Responsibilities:
- Build your DWH
- Build your DMP
- Transfer and store your data

As effective and fast as possible

---

<!-- _class: lead -->

# What is the most popular tool in DE?

---

![bg fit](images/spark.png)

---

# What `J(ava|VM)` dev should know

- Lazy sequences (streams, sequences, scala lazy)
- Functional operations
- SQL (or SQL-like)