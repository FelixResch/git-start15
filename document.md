---
title: FeMo.IO Markdown Editor
lang:
  - en
  - en-US
tags:
  - Markdown
  - Editor
secret: true
private: true
---

# About this app

This app enables you to write Markdown documents on your android device. While other apps either
 can be used as a viewer or an editor, this app combines editing, displaying and publishing of
 your Markdown document.

By using the integrated HTTP Server of the app the document is kept up to date at all times using
WebSockets. Other devices can also connect to the server if the app has been configured accordingly
and watch the changes made to the document in real time.

The app uses Attlasins implementation of commonmark, a specification of markdown, mostly compatible
with the original markdown but also extensible with extensions like:

* GHF Tables
* GHF Strikethrough
* Autolink
* YAML front matter

# Random Remarks

Alright got, rid of all them stupid remarks.

And now for the design... again....

And even more changes...

# Commonmark

For a full documentation of the commonmark specification see: http://spec.commonmark.org/0.26/ (As you can see, autolink is quite neat)

## Tables

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

## Strikethrough

This is ~~not~~ correct.

## Abbreviations

The HTML specification
is maintained by the W3C.

*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

# Authors

This app is maintained by:

* Felix Resch (felix.resch@femo.io)

---

And some others who still have to put their credentials here. All changes are commited and then pushed to a git repository.