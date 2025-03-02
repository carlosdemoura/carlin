# carlin

`carlin` is meant to introduce some nice macros to the LaTeX environment. It's worth highlighting the probabilistic macros, that automate the process of writing (conditional) probabilities, expectations, variances, etc. They might seem like overkill, but we strongly believe in a more syntactic LaTeX language (whatever that means).

Besides that, the probability functions automate the process of writing `\left` & `\rigth` when there are large inputs - and even `\middle` when we have conditional statements. By the way, the condition of these statements is an optional argument that comes after the mandatory one, which favors readability.

A draft of documentation is available. The name of the package is a tribute to [Carl Friedrich Gauss](https://pt.wikipedia.org/wiki/Carl_Friedrich_Gauss), the prince of statisticians.

Long live Gauss!

## Installation
You have to download `carlin.sty`, put it on the folder of your LaTeX Project and then call `usepackage{carlin}`.

This process can be quite a pain - especially when you consider that updates must be done by hand. I hope some day I'll have time to learn the engines of TeX so that I can upload `carlin` to CTAN.

I'll try to maintain this GitHub repo organised, and put the hashes of the "versions" of the main `.sty` file in `NEWS.md`, as well as the "release dates" of these versions in the heading of `carlin.sty`.
