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

```{admonition} <TYPE>: <Title>>
:class: seealso darkgreen dropdown
*<possible extra note/introduction to the resource>*
```<resource> % e.g. {video} https://www.youtube.com/watch?v=GhqTvWwMOYw

```{admonition} <TYPE>: <Title>>
:class: seealso darkgreen dropdown
```<resource> 

```


## REFLECT ON THIS TOPIC ADMONITION

```{admonition} Reflect on this topic!
:class: tip plum

< questions >
```


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

