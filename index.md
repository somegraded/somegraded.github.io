---
title: Home
layout: home
---

This is my first attempt to use the *bare-minimum* template to create a Jekyll site that uses the [Just the Docs](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md) theme. 

This is in the context of a Hackathon in the company I work[^1]. 

```sh
npm install 
npm start
```

# tasks

- [ ] Figure out how to show/hide some sections

# section 1 - show/hide feature

How can a section be shown/hide? We don't know yet. Maybe using `<details>`

<details markdown="block">
<summary>this is the whay!</summary>

## section 1a - what we know

First we need to see if the sections are inside a `<div>`. 

If not it will be difficult to join all of its paragraphs. 

## section 1b - what we can try

Another posibility is to add manuall a `div` tag enclosing the paragraphs.

In that way we have it them all together.

</details>

<details>
<summary>Table inside a container</summary>
 
| **head1**        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |
</details>

----
[^1]: [SimCorp](https://www.simcorp.com/).
