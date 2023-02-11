# Open for a surprise

- Namespace: picoctf/examples
- Type: static-make
- Category: General Skills - Sanity Challenge
- Points: 1
- Templatable: no

## Description

Participants have to just download the flag from one of our servers through a link with wget or curl or through their browser.

## Details
Download the flag the link {{url_for("flag.txt", "here")}}.

## Hints

- Download the file with extension .txt and open it in a text editor like vi or Notepad.

## Solution Overview

Download `flag` and open it.

## Challenge Options

```yaml
cpus: 0.5
memory: 128m
pidslimit: 20
ulimits:
  - nofile=128:128
diskquota: 64m
init: true
```

## Learning Objective

Test and verify your connectivity to our CTF

## Tags

- example

## Attributes

- author: Grace Tcheukounang
- organization: Cylab
