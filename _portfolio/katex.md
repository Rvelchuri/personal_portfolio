---
layout: post
title: Katex
feature-img: "assets/img/portfolio/katex.png"
img: "assets/img/portfolio/katex.png"
date: Febrauary 2022
---
KaTeX is a fast, easy-to-use JavaScript library for TeX math rendering on the web.Katex is a fast,lightweight javascript library for rendering math equations on the web using the TeX typesettting standards.It was created in 2014 by Emily Eisenberg and sophie Alpert while they working fro Khan Academy. Presumably, the K-A in KaTex refers to the Khan Academy(non-profit organization).

<script>
        document.addEventListener("DOMContentLoaded", function () {
            renderMathInElement(document.body, {
                // customised options
                // • auto-render specific keys, e.g.:
                delimiters: [
                    { left: '$$', right: '$$', display: true },
                    { left: '$', right: '$', display: false },
                    { left: '\\(', right: '\\)', display: false },
                    { left: '\\[', right: '\\]', display: true }
                ],
                // • rendering keys, e.g.:
                throwOnError: false
            });
        });
    </script>
<body>
    <h1>$ \TeX $ Examples</h1>

    <h2>Basic Syntax</h2>

    <ul>
        <li>
            <p>Text Mode vs. Math Mode</p>
        </li>

        <li>
            <p>$$ for Inline (aka Mathematics Mode)</p>
        </li>

        <li>
            <p>Inline vs. Display</p>
        </li>

        <li>
            <p>$$$$ for Display (aka Display Mathematics)</p>
        </li>

        <li>
            <p>\ for symbols and functions</p>
        </li>

        <li>
            <p>{} used with functions</p>
        </li>

        <li>
            <p>whitespace is ignored (for the most part)</p>
        </li>
    </ul>

    <p>This is Text Mode.</p>

    <p>$ This is what characters look like inside Math Mode. $</p>

    <p>$ \text{This is how to display text inside Math Mode.} $</p>

    <p>$$ \text{Display Mode is Centered on a separate line.} $$</p>

    <h2>Basic Math</h2>

    <p>Text Mode: 1 + 1 = 2</p>

    <p>Math Mode Inline: $ 1 + 1 = 2 $</p>

    <p>Math Mode Display: $$ 1 + 1 = 2 $$</p>

    $$1+1=2$$

    $$ 2 - 3 = -1 $$

    $$ 2 x 3 = 6 $$

    $$ 2 \times 3 = 6 $$

    $$ 5 / 2 = 2.5 $$

    $$ 5 \div 2 = 2.5 $$

    $$ \frac{1}{2} = 0.5 $$

    $$ \frac{3}{4} = 0.75 $$

    $$ 2^3 = 8 $$

    $$ \sqrt{4} = 2 $$

    $$ \sqrt[3]{8} = 2 $$

    $$ t_0 $$

    $$ $100 $$

    $$ \$100 $$

    $$ 100% $$

    $$ 100\% $$

    $$
    % this is a comment that will not render
    this is text \\ % this is how to add a new line
    \text{this is also text}
    $$

    <h2>Algebra</h2>

    $$ x + 2 = 5 $$

    $$ x = 5 - 2 $$

    $$ x = 3 $$

    $$
    x + 2 = 5 \\
    x = 5 - 2 \\
    x = 3
    $$

    $$ ax^2 + bx + c = 0 $$

    $$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

    <h2>Geometry</h2>

    $$ a^2 + b^2 = c^2 $$

    $$ A = \pi r^2 $$

    $$ 30\degree + 60\degree + 90\degree = 180\degree $$

    <h2>Trigonometry</h2>

    $$ \sin A = \frac{\text{opposite}}{\text{hypotenuse}} = \frac{a}{c} $$

    $$ \cos A = \frac{\text{adjacent}}{\text{hypotenuse}} = \frac{b}{c} $$

    $$ \tan A = \frac{\text{opposite}}{\text{adjacent}} = \frac{a}{b} =
    \frac{a/c}{b/c} = \frac{\sin A}{\cos A} $$

    <h2>Calculus</h2>

    $$ \lim_{h \rarr 0} \frac{f(a + h) - f(a)}{h} $$

    $$
    y = x^2 \\
    \frac{dy}{dx} = 2x
    $$

    $$ \int_a^b f(x)dx = F(b) - F(a) $$

    $$ \frac{d}{dx} \int_a^x f(t)dt = f(x) $$

    <h2>Physics</h2>

    $$ \sum \bold{F} = 0 \Leftrightarrow \frac{\text{d}\bold{v}}{\text{d}t} = 0
    $$

    $$ \bold{F} = m\bold{a} $$

    $$ \bold{F}_\textit{\textsf{A}} = \bold{-F}_\textit{\textsf{B}} $$

    <h2>Statistics</h2>

    $$ \bar{x} = \frac{1}{n} \Bigg(\sum_{i=1}^n x_i \Bigg) = \frac{x_1 + x_2 +
    \cdots + x_n}{n} $$

    $$ s = \sqrt{\frac{1}{N - 1} \sum_{i=1}^N (x_i - \bar{x})^2} $$

    <h2>Linear Algebra</h2>

    $$
    \begin{bmatrix}
    a_1 \\
    \vdots \\
    a_m
    \end{bmatrix}
    $$

    $$
    \begin{bmatrix}
    a_{1,1} & \cdots & a_{1,n} \\
    \vdots & \ddots & \vdots \\
    a_{m,1} & \cdots & a_{m,n}
    \end{bmatrix}
    $$

    $$
    \begin{alignedat}{3}
    2&x + y \space- &z &= &8 \\
    -3&x -y + 2&z &= \space&-11 \\
    -2&x + y + 2&z &= &-3
    \end{alignedat}
    $$

    $$
    M =
    \begin{bmatrix}
    \begin{aligned}
    &2 & &1 & -&1\space \\
    \space-&3 & -&1 & &2 \\
    -&2 & &1 & &2
    \end{aligned}
    \end{bmatrix}
    $$

    <h2>Other</h2>

    $$ \infty $$

    $$
    \alpha \beta \gamma \delta \\
    \epsilon \theta \iota \mu \\
    \sigma \phi \varphi \omega
    $$

    $$
    \TeX \\
    \KaTeX
    $$








