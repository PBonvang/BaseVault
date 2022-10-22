---
aliases: [] # Searchable synonyms and translations
---
Modified: `$= dv.current().file.mtime`
Tags: []
Subjects: [[Obsidian]]
****

# Templater
[Templater](https://github.com/SilentVoid13/Templater) provides advanced templating to your notes.
Templates are note snippets which can alter, add content to, move notes, and so much more. This makes it easy to standardize your notes and generally increase the speed of note taking.

# Quick LaTeX
[Quick LaTeX for Obsidian](https://github.com/joeyuping/quick_latex_obsidian) is as the name suggest a plugin which speeds up your LaTeX writing by implementing shortcuts such as / becoming `\frac{}{}`, auto enclosing sections after `^` and `_`. It also helps align in align environments and implements its own hotkeys for inserting templates in LaTeX environments.

# Quick switcher++
[Quick switcher++](https://github.com/darlal/obsidian-switcher-plus) makes it possible to search for headings in notes, thus expanding the searchable content of your vault.

# Excalidraw
<span class="centerImg">![[GettingStartedWithObsidian_ExampleDrawing]]</span>
[Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin) brings the power of handwritten notes to your Obsidian vault. It's a plugin build on top of the draw.io engine, with additional Obsidian features like embedding and linking notes, MOC creation, templates and much more. At some point it had OCR, but the underlying OCR library was discontinued, but there's talks of implementing a new OCR library.
This is truly a plugin worth checking out.

# Admonition
**NOW NATIVELY SUPPORTED IN OBSIDIAN:** [Obsidian Callouts](https://help.obsidian.md/How+to/Use+callouts)

[Admonition](https://github.com/valentine195/obsidian-admonition) provides beautiful blocks collapsible blocks which can be used to highlight theorems, methods and the like.

**Example:**
```ad-tip
title: Theorem 3.14 <br>  Central Limit Theorem
collapse: open

Let $\bar{X}$ be the sample mean of a random sample of size $n$ taken from a population with mean $\mu$ and variance $\sigma^{2}$, then
$$
Z=\frac{\bar{X}-\mu}{\sigma / \sqrt{n}},
$$
is a random variable which distribution function approaches that of the standard normal distribution, $N\left(0,1^{2}\right)$, as $n \rightarrow \infty$. In other words, for large enough $n$, it holds approximately that
$$
\frac{\bar{X}-\mu}{\sigma / \sqrt{n}} \sim N\left(0,1^{2}\right) .
$$

```
^theorem3-14

# Advanced Tables
Once you've tried to manually implement a markdown table, you'll want [Advanced Tables](https://github.com/tgrosinger/advanced-tables-obsidian). In short it automatically creates new rows and columns by tab or enter, and maintains spacing in your markdown so it's actually possible to determine which column you're in.

# Extended MathJax
[Extended MathJax](https://github.com/xldenis/obsidian-latex) is a plugin which allows you to implement your own LaTeX commands. For example when you're tired of writing: `\mathrm{e}` and simply want to be able to write: `\e` you can implement exactly this functionality using this plugin.

# Advanced Cursors
Once you've gotten used to the multi cursor functionality of an IDE like vs code, you never want to go back. [Advanced Cursors](https://github.com/SkepticMystic/advanced-cursors) brings exactly this functionality to Obsidian.

# Dataview
[Dataview](https://github.com/blacksmithgu/obsidian-dataview) provides an API to access and query metadata of notes. For example providing the "modified" date in the top of this file.

Or getting a list of files related to this file
```dataview
LIST
FROM "" WHERE contains(file.outlinks.file.name, "Useful community plugins") OR contains(file.inlinks.file.name, "Useful community plugins") 
SORT file.name ASC
```

# Jupyter
[Jupyter](https://github.com/tillahoffmann/obsidian-jupyter) allows you to run python notebook cells in your notes, effectively creating a notebook in your note.

# References