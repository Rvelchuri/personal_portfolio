---
layout: post
title: mermaid
img: "assets/img/portfolio/mermaid.png"
date: 2022-02-20
---

Mermaid is a simple **markdown**-like script language for generating charts from text via **JavaScript**. Mermaid lets you generate diagrams and flowcharts with Markdown-like syntax. It's easy to use, free, and open source. Mermaid lets you simplify documentation and avoid bulky tools when explaining your code.


<div class="mermaid">
graph TD 
    A(how to cook rice) --> B(take instapot empty bowl and empty cup)
    B --> C(put 1 cup of rice in the bowl)
    C --> D(rinse with water 3 times)
    D --> E(now add 2 cups of water)
    E --> F(wipe the bottom of bowl and put the bowl in instapot docker )
    F --> G{is instapot powered on?} --> |Yes| I(close lid and set instapot to Rice mode)
    G --> |No| H(plug in and turn on) -->I
  
</div>

## making Coffee

<div class="mermaid">
graph TD
   A(Coffee machine <br>not working) --> B{Machine has power?}
   B -->|No| H(Plug in and turn on)
   B -->|Yes| C{Out of beans or water?} -->|Yes| G(Refill beans and water)
   C -->|No| D{Filter warning?} -->|Yes| I(Replace or clean filter)
   D -->|No| F(Send for repair)
</div>





