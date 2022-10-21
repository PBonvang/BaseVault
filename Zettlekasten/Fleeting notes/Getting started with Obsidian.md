---
cssclass: clean-embeds
aliases: [] # Searchable synonyms and translations
---
Modified: `$= dv.current().file.mtime`
Tags: []
Subjects: [[Obsidian]]
****

# 1 - Markdown
Obsidian implements the basic markdown syntax with some additional features, such as direct linking, embedding, tagging and so on. We'll get to these additional features later on. First step is to understand markdown, which will be your notes language.
A good and quick guide for basic markdown syntax can be found here: https://www.markdownguide.org/basic-syntax.

# 2 - Linking your thoughts
*Notes are only as valuable as its context.*
Notes by themselves can be useful, but usually relies heavily on the knowledge surrounding it. It's very hard to understand curl of a vector field without first understanding what a vector field is. Thus the context of a note is just as important as its content.

**Linking syntax:**
In Obsidian linking is done using double square brackets enclosing the name of the file, e.g. `[[Obsidian]]` = [[Obsidian]].

**[[Note linking theory|Linking theory]]:**
How you link and structure your notes is really a personal preference. The thought is to model how you think, and thus every vault is unique in some sense. However there's some theory which might be nice to know before you select your note structure. See [[Note linking theory]].

# 3 - Core functionality

**Aliasing:** `aliases` is a metadata attribute used by *Quick Switcher* (`ctrl+o`) as alternative names for the notes. If a concept has multiple names all referring to the same concept, aliases for the file allows multiple names for the same file. It can also be used for translations of the concepts name, allowing you to search for concepts in multiple languages.
To add the aliases to the metadata simply put the following in the top of the file:
```markdown
---
aliases: [] # Searchable synonyms and translations
---
```

**Tagging:** Adding tags (\#tag) to notes can have many meanings, some use it for a separate index for your notes, e.g. tagging all notes related to a course with a corresponding tag. I've found it most useful to use tag for note types. That way I can filter out certain note types like lectures, utility files and other non-permanent notes in my graph view, giving a better overview of my [[critical mass]]. 

**LaTeX:** Obsidian incorporates LaTeX natively using the [MathJax](https://www.mathjax.org/) library. This means most of the LaTeX functions you know and love, is available in Obsidian in two formats: inline and block.
Single \$ will create inline LaTeX, e.g.  `$\frac{\sqrt{a}+1}{\delta}$` = $\frac{\sqrt{a}+1}{\delta}$.
Double \$\$ creates a full LaTeX block, `$$\frac{\sqrt{a}+1}{\delta}$$` = 
$$\frac{\sqrt{a}+1}{\delta}$$
To make typing LaTeX much faster use the [Quick LaTeX](https://github.com/joeyuping/quick_latex_obsidian) plugin.

**Programming notes:** Obsidian incorporates native code blocks, allowing code highlighting and formatting. Like the LaTeX blocks there's both an inline and block.
Inline code cells are added using two backticks: \`\` and can't format or highlight code, e.g. `int a = 10`.
Code blocks however can format and highlight code, and is implemented using 6 backticks. To get the highlighting of the specific language add the language after the first 3 backticks, e.g.
```python
from functools import lru_cache

@lru_cache(maxsize=100)
def Fib(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return Fib(n-1) + Fib(n-2)
```

**Graph view:** Obsidian has two graph views: Global and local.
- The global graph view displays all of your notes and can be a good place to find "Ghost" clusters
- The local graph view displays the notes linked to the currently open note, and is great when looking for a concept related to a subject or another concept.

<span class="centerImg">![[VaultGraphMatStatExample.png]]</span>

**Command prompt:** `ctrl+p` will open a prompt with the various core and community commands.
Often used commands:
- **Reload app without saving:** Reloads Obsidian, which is often required after installing a new plugin or changing of settings.

# 4 - Plugins
There exist two plugin versions: Core and community. The core plugins are fundamental Obsidian functionality which can be toggled on an off. The full list can be found in settings under *Core plugins*.

Community plugins are as the name suggests plugins created by the community. These are what really sets Obsidian apart from other note taking systems, as it means there's usually a plugin which will solve our problem, and we don't have to wait for the Obsidian developers to implement a solution.
If you feel like some functionality is missing from your system, do an internet search and you'll probably come across a community plugin. Else browse them in settings under *Community plugins* > *Browse*.

See [[Useful community plugins]], for my highlighted community plugins.

# 5 - External tools
Working with Obsidian fuels an automation mindset, if you're tired of doing something over and over again, we look for a solution to automate it. Mostly solutions can be found in the community plugins, but sometimes we must look elsewhere.

Some tools which you might find helpful:
- [Photopea](https://www.photopea.com/): Photopea is an online photoshop copy which is free to use and surprisingly good. If you need a image cropped, the back ground removed, colours inverted or generally change an image, this is a great tool.
- [Mathpix](https://mathpix.com): Mathpix is an online OCR made for LaTeX translation. This is a real time saver, instead of having to copy long LaTeX formulas simply screen shot it, through it in Mathpix and voila you've got the formula in a nice and modifiable format. Mathpix has a free trial, which works just fine if you're not copying full PDFs worth of text, else their subscription is less than 50 DKK per month.
- [Zotero](https://www.zotero.org/): Zotero is a personal research assistant, which keeps track of read articles and papers, seen videos, visited sites that you wish to refer to in the future. It's essentially a library of sources which automatically generates citations and bibliographies links. Combined with the [Zotero obsidian](https://github.com/mgmeyers/obsidian-zotero-integration) plugin, it becomes even easier.

# 6 - Systemic note taking / Note mindset
Once you've got the basics of using Obsidian down:
- Basic markdown
- How to link in a meaningful way
- How to use plugins

We're ready to continue on to the discussion of how to structure your notes and their interactions in a meaningful way. We're now going talk about the following questions:
- What is a [[Smart notes|smart note]]?
- How do I take meaningful notes?



The structure of a personal vault is and should heavily depend on the person.
Are you a student in need of a encyclopedia where you can quickly find formulas, methods and theorems it's probably more useful to implement a wiki like structure in your notes. Simply referencing other notes when mentioned directly in the text or in a *See also* section.


- Wiki
- Zettlekasten
- Note standardization
# 7 - Common mistakes

# 8 - Tips and tricks
- [[Useful hotkeys]]
- [[Note taking vocabulary]]



# References
- [[Smart notes]]