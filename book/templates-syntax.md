# HEADINGS AND SUBHEADINGS

- if there is only one subheading, this should not appear in the index on the right column. 


# ADD IMAGES

First, upload the image in the "figure" folder. 

Then, use the below syntax: 

```{figure} ../figures/<name>.jpg
---
width: 80%
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

```{admonition} Delve deeper into this subject! 
:class: note grey 
*If you want to learn more about this topic, consider one of the following material(s):*

```{admonition} <TYPE>: <Title>
:class: seealso darkgreen dropdown
*<possible extra note/introduction to the resource>*
```<resource> % e.g. {video} https://www.youtube.com/watch?v=GhqTvWwMOYw

```{admonition} <TYPE>: <Title>
:class: seealso darkgreen dropdown
```<resource> 

```


## REFLECT ON THIS TOPIC ADMONITION

```{admonition} Reflect on this topic!
:class: tip plum

< questions >
```

## GRASPING THE CONCEPT
This card is a way to propose alternative activities to students/teachers. Each activity should be a dropdown. Following is an example. 

:::::{card}

**Grasping the concept:** consider doing one of the following <n> activities.

```{admonition} How do you interact with metadata in your everyday life?
:class: tip plum dropdown

All digital objects are automatically stored alongside metadata. If you are looking for a file in your laptop, you may search by name, but also filter by size, date of creation, author, etc. If you are looking for a specific picture on your phone, you may check the location and dates. When navigating your email inbox, you may also filter by sender and dates. All of these, are metadata. 
```

```{admonition} VIDEO: What is metadata? A visual story
:class: seealso darkgreen dropdown
*Would you like to have a more visual explanation of metadata? Check out this video!*
```{video} https://www.youtube.com/watch?v=L0vOg18ncWE
```
:::::


# MARGINS 

Margins can be used to provide extra information or context. For example, to provide a reference to the relevant learning goals. 


````{margin}


<text>


```` 


## LEARNING GOALS IN MARGIN

````{margin}

```{admonition}
:class: tip palegreen
<text>

```

```` 

# QUESTIONS
% https://teachbooks.io/manual/_git/github.com_TeachBooks_TeachBooks-Questions/main/MANUAL.html

# COLOURS
% https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/named-color

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