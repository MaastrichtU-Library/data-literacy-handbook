# HEADINGS AND SUBHEADINGS

- if there is only one subheading, this should not appear in the index on the right column. 


# INTERNAL LINKS

 [<TITLE OF LINK>](../<path to the file>/<file-name.md>)
 [For Bachelor's students](../paths/BAstudent.md)


# OTHER LINKS

## Markdown Inline Links

[Link text](https://www.markdownlang.com)
[Link with title](https://www.markdownlang.com "Link title")

## Markdown Reference Links

[Link text][ref]
[Link text][]

[ref]: https://www.markdownlang.com "Optional title"
[Link text]: https://www.markdownlang.com

##  Markdown Autolinks

<https://www.markdownlang.com>
<email@example.com>

## Markdown Anchor Links

[Jump to heading](#heading-name)
[Back to top](#top)

## referencing figure 
{numref}`Figure {number} <name of the figure>` 

# ADD IMAGES

First, upload the image in the "figure" folder. 

Then, use the below syntax: 

```{figure} ../figures/<name>.jpg
---
width: 80%
name: <figure name> %add this line if need to reference to it   
align: center
---
Research Data Lifecyle {cite:p}`turing-way-scriberia-images` 
```
- note that emphasis should only be made via italics.
- note that if you are citing a source you need to make sure that the source is included in the references.bib file.

# ADMONITIONS: 

% https://myst-parser.readthedocs.io/en/latest/syntax/admonitions.html

## DELVE DEEPER ADMONITION
This is a card with admonitions inside or an admonition into admonitions
- Title: Delve deeper into this subject!
- Sentence:*If you want to learn more about this topic, consider one of the following material(s):*
- Each item needs to include
    - <TYPE>: <Title>
    - e.g. <VIDEO> <How to be happy>

````{admonition} Delve deeper into this subject! 
:class: note grey 
*If you want to learn more about this topic, consider one of the following material(s):*

```{admonition} <TYPE>: <Title>
:class: seealso darkgreen dropdown
*<possible extra note/introduction to the resource>*
```<resource> % e.g. {video} https://www.youtube.com/watch?v=GhqTvWwMOYw
```
```{admonition} <TYPE>: <Title>
:class: seealso darkgreen dropdown
```<resource> 
```
````
**example**
````{admonition} Delve deeper into this subject! 
:class: note grey 
*If you want to learn more about this topic, consider one of the following material(s):*


```{admonition} VIDEO: Funky file formats (Ange Albertini)
:class: seealso darkgreen dropdown
```{video} https://www.youtube.com/watch?v=hdCs6bPM4is
```

```{admonition} ARTICLE: Interoperability in education
:class: seealso darkgreen dropdown
```{iframe} https://www.surf.nl/en/themes/interoperability/key-concepts-of-interoperability-in-education
```
````

## REFLECT ON THIS TOPIC ADMONITION

```{admonition} Reflect on this topic!
:class: tip plum

<span style="color:black"> 

< questions >

</span>
```

## DATA HORROR STORY

```{admonition} Data horror story
:class: warning orangered dropdown

<span style="color:black"> 

<question question text text>

</span>

```

## GRASPING THE CONCEPT
This card is a way to propose alternative activities to students/teachers. Each activity should be a dropdown. Following is an example. 

:::::{card}

**Grasping the concept(s):** get started with some of the following activities.

```{admonition} <question>
:class: tip plum dropdown

<span style="color:black">
<content content content>
</span>.
```

```{admonition} VIDEO: What is metadata? A visual story
:class: seealso darkgreen dropdown
*Would you like to have a more visual explanation of metadata? Check out this video!*
```{video} https://www.youtube.com/watch?v=L0vOg18ncWE
```
:::::

# ATTRIBUTING ADAPTED TEXT FOR ENTIRE SECTIONS

```{white}
The content in [this section](#title) is adapted from: {cite:t}`key`.
```

e.g.
```{white}
The content in [this section](#data-formats) is adapted from: {cite:t}`how-to-fair-file-formats`.
```

# MARGINS 

Margins can be used to provide extra information or context. For example, to provide a reference to the relevant learning goals. 


````{margin}


<text>


```` 


## LEARNING GOALS IN MARGIN

````{margin}
```{admonition} Competences
:class: tip dropdown cornflowerblue

<span style="color:black">
This section will help you:

- <competence1>
- <competence2> 
</span>
```
````

```` 

# QUESTIONS
% https://teachbooks.io/manual/_git/github.com_TeachBooks_TeachBooks-Questions/main/MANUAL.html

# COLOURS
% https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/named-color

# FORCE COLOUR FOR SPECIFIC TEXT
<!--
Source - https://stackoverflow.com/a/35485694
Posted by Waylan, modified by community. See post 'Timeline' for change history
Retrieved 2026-08-13, License - CC BY-SA 4.0
-->

<span style="color:blue">some *blue* text</span>.


# CITING
% https://teachbooks.io/manual/features/apa.html 

# SMALLER FONT
<sub>your content here</sub>

# HIGHLIGHT
<mark>your content here</mark>


# Syntax exercises from teachbook: 
% https://teachbooks.io/template/syntax_exercises.html

As user type 3 you will work primarily in `.md` (Markdown) or `.ipynb`(Jupyter Notebook) files. In TeachBooks, `.md` files contain text-based content with formatting, while `ipynb` files contain both text and executable code cells. `.md` files are much easier to edit online, so let's start with those!

The more you write, the more different types of content you'll want to use. [JupyterBook v1 itself provides a cheatsheet](https://jupyterbook.org/v1/reference/cheatsheet.html) which will come in handy!