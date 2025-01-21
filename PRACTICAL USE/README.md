### Pre-requisites:
- Node.js
- vscode preferred if you want to follow along

### Getting Started with Docusaurus

Open up the terminal within vscode

We will begin by using Docusaurus's quick start command:  

```bash
npx create-docusaurus@latest my-website classic
```

1. **Proceed**: When prompted, type `y` to continue.  
2. **Choose Language**: You will be asked to use either JavaScript or TypeScript.  
   Use the arrow keys to make your selection. (I will use **TypeScript**.)

---

### Building the Site Template

Once you've made your selection, give it some time to build your site template.

---

### For the Lesson, use the automatically created sandbox

Please use the sandbox I have already created for the In-person side of the Lesson
[Click Here](https://codesandbox.io/p/devbox/priceless-dew-t8j3dt?workspaceId=ws_S4EegmuMtqu3jPpjvArW38)

*You must sign in* and then fork the box to *be able to edit*

### Working in the `./blog` Folder

By default, the `./blog` folder contains a few example blog posts to help you get started.  
You can customize or add your own posts to build your blog content.

This is where our lesson will work within
---

### Viewing the markdown wiki/blog as a webpage

When you are done editing, run these commands in terminal to start a local server:

```bash
cd .\my-website\
npm start
```

It will automatically open your browser as it builds the sever

Once it is build, navigate to your blog page, 
Here you will see all of the markdown files compiled as a web friendly blog

To close the server use 'Ctrl + C' and type 'y'

### Other practical examples:

Github uses markdown all the time - your READme file is primarily formatted using markdown
- It can get pretty crazy: [example](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

Note Taking Apps commonly support markdown
- Best example is Obsidian - [download here](https://obsidian.md/download)
   - In fact, the code of this app is ~70-80% written in Markdown (mainly for UI stuff)

---
### Markdown Reference guide:

## Headings
```md
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Text Formatting
```md
**The quick brown fox jumps over the lazy dog.**
__The quick brown fox jumps over the lazy dog.__
<strong>The quick brown fox jumps over the lazy dog.</strong>
**_The quick brown fox jumps over the lazy dog._**
<strong><em>The quick brown fox jumps over the lazy dog.</em></strong>
~~The quick brown fox jumps over the lazy dog.~~
```

## Links and Images
```md
[Google](https://www.google.com)
![Alt text](https://via.placeholder.com/150)
```

## Tables
```md
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1    | Data     | More     |
| Row 2    | Data     | More     |
```