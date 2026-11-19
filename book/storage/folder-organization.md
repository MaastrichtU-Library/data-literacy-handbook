# How to organize data?

````{margin}
```{admonition} Competences
:class: tip dropdown cornflowerblue

<span style="color:black">
This section will help you:

- implement a coherent and consistent structure when storing data
</span>
```
````

When working with data, it is important to have a good system to store and organize your different files (including data, metadata, documentation, analysis scripts etc.). A good organizing system is essential to ensure that you can easily **navigate** and **retrieve** the information needed, but it is also needed to ensure the **security** of your data and the **privacy** of your participants, if you have any. Moreover, when working in research groups, a shared understanding of how you plan to structure your (data) files is essential to ensure smooth **collaboration**. 

:::::{card}

**Grasping the concept:** consider doing one of the following activities.

```{admonition} Reflect on your current organization systems
:class: tip plum dropdown
<span style="color:black"> 

- How do you organize files on your laptops? 

- Do you have one system that you apply to your hobby-related files, your university-related files, your health-related files? 

- Have your system evolved through the years? 

- What seems to work well for you? What could be improved? 

- If you have (had) any shared folders, how were these organized? How did you land on that system? 

</span>


```

```{admonition} VIDEO: File paths 
:class: seealso darkgreen dropdown
*Would you like to have a more narrative explanation of folder organization? Check out this video!*
```{video} https://www.youtube.com/watch?v=y6LUQLUEV8g

% Project structure (part 4) -Danielle Navarro
% [maybe move somewhere else?]
```

```{admonition} VIDEO: Where do projects live?
:class: seealso darkgreen dropdown
*Would you like to have a more narrative explanation of folder organization? Check out this video!*
```{video} https://www.youtube.com/watch?v=q8cMQOt-V0Q&list=PLRPB0ZzEYegPiBteC2dRn95TX9YefYFyy&index=7

% Project structure (part 6) -Danielle Navarro
```


```{admonition} Classroom activity [TO DO]
:class: tip mediumslateblue dropdown

<span style="color:black">
a. have physical pieces of papers wit some naems and sked students to put these in different folders.

b. ask students to look into each others folders? 

c. ask students to draw something based on others instructions, se wee what goes wrong.

% see examples love data week


</span>
```

:::::


There are many different systems for organizing files, when it comes to your data, here are collected **10 best practices** that you can follow to ensure that your data is well organized. 

## 1. Document your structure
It may not seem important to document your folder structure, as you may think that you "know your folder like the back of your hand". However, documenting the structure of your folder can be a valuable process to:

- think through your data and your storage needs; 
- assess your file management system;
- easily be able to locate and retrieve the information needed following a period of not actively working within the folders.

Moreover, if you are working in a team, documenting your structure ensures that everyone in the team is aligned. If your team changes members throughout the project, this documentation is also helpful in the onboarding of new members. 

The most straightforward way to do this, is through a {term}`README file`. In there, you can describe your structure as well as your rationale for it. You can learn more about README files in the [documentation chapter](../storage/documentation.md)

```{figure} ../figures/file-management-manual-no-title.jpg
---
width: 80%
align: center
---
File organization {cite:p}`turing-way-scriberia-images` 
```


## 2. Organise folders hierarchically... 
Structure often means hierarchy. When it comes to your data folders, that can also be helpful. Parent folders or main folders contain subfolders which may also contain further subfolders. The result is a tree-like hierarchy that organizes files based on categories. This tree structure can help you find your data and documentation faster.

## 3. ... but recognise when the hierarchy is not serving you anymore 
However, make sure that you do not create **unnecessary** nested levels of folders. As a rule of thumb, three levels of nested-ness in your main folder should be enough to keep you organised. If you have to access more than three subfolders before finding a file, you may want to reassess your system: do you really need all these subfolders? 

Take the following (fictitious) example: 
Here is the tree structure of a research project in which part of the main folder "Documentation" is specified. In this folder templates for consent forms and templates for the interview guides are collected. As the research team will be working with both Dutch-speaking and English-speaking participants, files are provided in each language.
 
```{figure} ../figures/folder-structure-bad.png
---
width: 100%
name: folder-structure-bad  
align: center
---
Folder structure example (to improve)
```
In {numref}`Figure {number} <folder-structure-bad>` you can see that level4 subfolders are created in order to differentiate the drafts and final versions of templates for each language. You can also notice that in some subfolders there is only one file, which might make the subfolder unnecessary. In fact, by implementing a good [naming system](../storage/naming-conventions.md), locating a file within a folder is less tedious than following the path into the folder. As a rule of thumb, if you have less than 10 documents in a folder you may not need to create a subfolder. Then again, use your judgement and personal preferences to assess what would work best in your context. Implementing a clear naming convention, the folder structure can be simplifies as follows:    

```{figure} ../figures/folder-structure-fixed.png
---
width: 100%
name: folder-structure-fixed  
align: center
---
Folder structure example (better practices)
```
In {numref}`Figure {number} <folder-structure-fixed>`, all sub-folders containing only one file are substituted in with clear file names. Moreover, for what concerns the "Interview guide" folder, all drafts are collected in one subfolder as they probably will not need to be accessed as often once the final version is developed. 

## 4. Be proactive about creating (sub)folders 
Ideally, you should have your folder structure figured out before you receive your data. If not, you may find yourself saving your data in a folder or creating some kind of organisation thinking that it is "temporary" and that you will go back to it and re-structure and sort your files later. In practice, you might not get back to it anymore and the temporary structure might end up confusing you in the longer run. 

Ensuring that you have your folder structure figured out (subfolders included) at the beginning of your project makes your life easier as you will simply need to save your data or other files in the ready place instead of having to go through the labour of thinking about your structure every time you have a new file. This can lower fatigue and limit errors. 

% consider adding analogy of building the house: whole house and then divide people in each different room instead of building a room each time a new person moves in. 

## 5. Proactively enforce access control 

When creating your folder structure, you should also already think about who will need access to which folders and proactively assign the correct rights of access to each one of your collaborators. To keep an overview of these rights, you can rely on an access control matrix in which you specify by file or by folder who has access to what content. {numref}`Table {number} <access-control-matrix>` provides an example of an access control matrix for which there are two levels of access, namely editing rights and viewing rights. 

```{table} Example of access control matrix
:name: access-control-matrix

|   |<span style="font-weight:normal">Folder A</span> |<span style="font-weight:normal">Folder B</span> |<span style="font-weight:normal">Folder C</span> |<span style="font-weight:normal">Folder D</span> | <span style="font-weight:normal">Folder E</span> | <span style="font-weight:normal">File X</span> |
|---|---|---|---|---|---|---|
| Collaborator 1 | edit |edit   |edit   |edit   |edit   |edit   |
| Collaborator 2 | edit |edit   |view   |view   |view   |       |
| Collaborator 3 |      |edit   |view   |       |       |       |
| Collaborator 4 |      |       |       |edit   |view   |       |
```

## 6. Avoid duplicates... 
Each file should belong to one folder. Duplicating files can increase complexity and errors. For example, if you update the content of a file without updating its duplicate in the different location you might rely on an out-fo-date version in the future. 

If you are working in a storage solution that allows you for creating links or hyperlinks as objects within a folder (cloud storage solutions oftentimes provide this service), you can rely on this feature to have multiple "entry points" to your file in the different folders.

*! note that avoiding duplication of files does not mean avoiding having [back-ups](../storage/backup.md) for your file!*

## 7. ... but preserve raw data unmodified! [TO DO]
Your raw data is your treasure, do not modify it. Keep it unmodified stored separate and work on a copy.

what if the data is online? e.g. blogs, articles, atc? Still recommend having a copy because if you just save links these may break!

Horror story from fasos!!start organizing from the beginning! IF you only have link and thye break that is not great...

Raw data are to look at, not to touch. 

## 8. If working with personal data, add a layer of separation between your raw data and your pseudonymised or anonymised one [TO DO]

[TO DO: choose if keep the link to glossary in the title, I think that is too much]
If working with {term}`personal data <Personal data>`, consider separating your {term}`raw data <Raw data>` from your {term}`pseudonymised <Pseudonymisation>` or {term}`anonymised <Anonymisation>` data. This increases the protection of your participant's privacy. Separation means at the very least keeping these data in different folders. The more sensitive the data, the bigger the separation that you want to implement: different storage solutions, different access rights, different encryption and encryption keys. 

% refer to chapter on privacy and security?

## 9. Regularly assess your file management system
Micro-assessments happen every time you need to put a file in a folder. If you find yourself needing struggling to understand where to place it or, vice-versa, if you find yourself struggling with finding files within your folders, you may want to reflect why the current system is not working. 

**!** Whenever you are assessing your file management system, remember to update your README file if you incur in structural changes. 

## 10. Stick to it 
The system you set up is not going to be perfect, but in order to be effective you must commit to it and stick to it, at least for a little bit, before reassessing. 


````{admonition} Delve deeper into this subject! 
:class: note grey 
*If you want to learn more about this topic, consider one of the following material(s):*

```{admonition} VIDEO: Creating templates for folder structures
:class: seealso darkgreen dropdown
*<possible extra note/introduction to the resource>*
```{video} https://www.youtube.com/watch?v=zBInvQQEhuY

% Project structure (part 5) - Danielle Navarro
```

```{admonition} Procedure to create a folder structure
:class: tip plum dropdown

<span style="color:black"> 

[TO DO: INCLUDE EXAMPLE TEMPLATE FROM FASOS?]

🧠 Step 1: Think about your project's needs.
- what data, documentation and other files will you be collecting? 
- if you are working in a group, will everyone need access to all files?

🧭 Step 2: Create your level1 structure.
 Based on your answers above, what kind of level 1 folders will be needed? Lay the foundation of your new structure and your README file.

🏗️ Step 3: Think about your level 2 and level 3 structure.
You might have already started to create sub-folders. Refine your level 2 and 3. Go into each level 1 folder you have created and think about the subfolders that make sense for you there. 
Try to be as extensive as possible and think instead in terms of which data and files you may also have in the future. Creating the structure now will reduce your fatigue later as you will only have to sort your documents and not also think about whether to create a new folder. 
Do not forget to update your README file accordingly!

🏖️ Step 4: Test, polish and enjoy. 
You may want to think about asking a friend to look at your structure and talk them through it to see if it is clear for you. To test if your structure is "robust enough" for the most general scenarios, answer the following questions: 

1. Do you have a general README file? Where is it located? 
2. Do you know where you will place your {term}`personal data <Personal data>` 
[TO DO: END THIS QUESTION LIST!]

If you clearly (and quickly) knew where to place the above files, your folder structure may be ready to go! If not, consider thinking about it a little longer. 

But all in all, congrats, at this point you have a new folder structure! Remember to stick to it and keep your README file updated. 

</span>
```


```{admonition} Procedure if you already have a folder structure that you would like to restructure
:class: tip plum dropdown

<span style="color:black"> 

Restructuring a folder is quite the task. It is not a 5-minute task, and we advise you to follow this procedure as it gives you small tasks to achieve your goal. Try to complete one step at a time, and one step per "restructuring session". 

🧭 Step 1: Create your level1 structure.
Lay the foundation of your new structure. For this, think about the way you work in relation to the best practices introduced above. In practice: 

- Create these folders as empty folders, do not just rename the folders you already have
- Create a "Temporary sort" folder 
- Create an "Archive" folder (which you can use for any files that do not need to be kept)
- Create a README file and start editing it

🧹 Step 2: Move EVERYTHING in the "Temporary sort" folder.
Move all of your old/original folders, files, etc. that are now at the level1 to your "Temporary sort" folder. 
At this point, you should have, on level1, only your new folder structure and your README file.

🏗️ Step 3: Think about your level 2 and level 3 structure.
At this point, your folder looks exactly how you will want it at the end, for level one. This is the time to start thinking about the next levels. You may already have created some subfolders, that is great. Refine your level 2 and 3. Go into each level 1 folder you have created and think about the subfolders that make sense for you there and create them. 
Try to be as extensive as possible. Do not only think in terms of the documents and files that are now in your "Temporary sort", think instead in terms of which data and files you may also have in the future. Creating the structure now will reduce your fatigue later as you will only have to sort your documents and not also think about whether to create a new folder. 
Do not forget to update your README file accordingly!

📤 Step 4: Sort your files in your new structure. 
Now that you have your whole structure, you can start filling it with your documents. For each of the documents in your "Temporary sort" folder, follow this procedure:

[TO DO: ADD A DIAGRAM TO DESCRIBE THE PROCEDURE TO FOLLOW]

Notes:

- At this point of the process, it should be very rare that you need to create a new folder for lvl1
- Do not forget to update your README file if you change something in your structure

🏖️ Step 5: Polish and enjoy. 
You may want to still rename a few files and give one last check to your README file to make sure that it is documenting your final structure. But all in all, congrats, at this point you have a new folder structure! Remember to stick to it and keep your README file updated. 

</span>
```
````

