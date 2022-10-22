---
aliases: [] # Searchable synonyms and translations
---
Modified: `$= dv.current().file.mtime`
Tags: [#Project/Obsidian101]
Subjects: [[Obsidian]], [[Getting started with Obsidian]]
****

# 1. Basics
## a. Headings
**Make 3 headings of different importance:**

### h3
#### h4
##### h5

## b. Linking and embedding
**Link to another file:**
[[Getting started with Obsidian]]

**Create a custom/user-defined section in this file:**
^ex1

**Link to the custom section you just created:**
[[#^ex1|Exercise 1]]

**Link to a section in another file:**
[[Getting started with Obsidian#1 - Markdown]]

**Embed any section:**
![[Creativity, Steve Jobs#^quote]]

**Create a link to a website:**
[duckduckgo](https://duckduckgo.com)

## c. Images
**Embed an image:** (Either save a image to BaseVault/ZettleKasten/Attachments/Images, or use an existing image)
![[QuickLatexExercise.svg]]

**Embed a screenshot:**


**Center an embedded image:** (Perhaps use a template?)
<span class="centerImg">![[QuickLatexExercise.svg|200]]</span>


**Change the size of one of the previously embedded images.**


## d. Code blocks
**Implement a code block with correct highlighting:**
```python
print("Hello world")
```

## e. Escaping
**Escape the required symbols in the following paragraphs:**

The brain fuck compiler is located at: c:\\path\\to\\brain_fuck.c

To embed a note simply write: `![[Obsidian101]]`

**Escape a dollar sign:**
\$

## f. Tables
**Create the following table:** (Lower right corner is code)
<span class="centerImg">![[TableExerciseTable.png|300]]</span>



## g. HTML
**Colour the following paragraph:**
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>


# 2. Shortcuts
**Insert the keys for the shortcuts in the following table:**

| Shortcut                             | Keys |
| ------------------------------------ | ---- |
| Make bold                            | ``   |
| Make italic                          | ``   |
| Open settings                        | ``   |
| Make codeblock                       | ``   |
| Open command prompt                  | ``   |
| Make hyperlink                       | ``   |
| Open note (Quick switcher)           | ``   |
| Go back to previously opened note    | ``   |
| Go forward to previously opened note | ``   | 

```ad-warning
title: Answer
collapse: close

See [[Useful hotkeys]]
```

# 3. Plugins
**(Templater) Insert a template:**


**(Quick LaTeX) Write the following LaTeX expression using the shortcuts from Quick LaTeX:**
<span class="centerImg">![[QuickLatexExercise.svg|250]]</span>

```ad-warning
title: Answer
collapse: close

$$\A=\frac{\delta}{\pi+b^{2}}\approx \left(\frac{9}{10}\right)^{2}$$
or
$$\mathbf{A}=\frac{\delta}{\pi+b^{2}}\approx \left(\frac{9}{10}\right)^{2}$$
```


**(Dataview) Get the creation date of this file:**
`$= dv`

# References
- https://www.markdownguide.org/basic-syntax