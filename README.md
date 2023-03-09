
# Hosting A Resume Using GitHub Pages and Markdown


### Purpose of a README
--------------

Hello and welcome to my Markdown tutorial where we will look at the techniques and tools you can use with Markdown and later be able to use those tools and techniques to further your knowledge of how to properly write a Markdown. First of all, what is Markdown? Markdown is a lightweight markup language that is easy to read. It is like an easier version of writing HTML and used for many different things, most notably as an overview for a project.  Inside a project you will likely find a README.md file that includes documentation about their project, how to run it, if there are any bugs involved, etc. 


### Prerequisites
-------------
To start writing markdown you are going to need an editor. There are plenty of markdown editors you can easily find online for free such as Typora. I use Visual Studio Code, which is not necessarily the best for writing Markdown, but enough for what I need with its built-in features and extentions.

Before continuing you need to have some sort of basic knowledge of markdown. I suggest looking at one of the two markdown tutorials that can be found under [More Resources](#more-resources) towards the bottom of the page. 

Once you know a bit of how Markdown works you are ready to learn some recommendations of techniques you could use to improve your skills of using Markdown.  

When writing a markdown you want to think about your reader. You want you content to be discoverable, easy to find. If no one is reading your documentation, then who is it for? You are writing for your reader and no one else.


### Instructions
-------------

#### Hosting a Resume

The goal we want to accomplish is to host your resume in a static site generator. Static sites are great in the fact that they are much easier to manage compared to your own website. Using static websites allows you to easily share your documentation with others. Make a new resume in markdown.

If you already have a resume, convert it to markdown. Once you have your markdown file ready we can upload it to GitHub Pages which is a static site generator.

Our end goal is to host your resume like this.

[Resume Gif](.gif)

Lets begin the process to host a Resume using GitHub Pages!


__Step 1: Create New Repository__

If you have not already logged in to GitHub, do so now. Alternatively you can do this with both [GitHub Desktop](https://desktop.github.com/) and the browser. For the purpose of this example, I will be using GitHub on the Browser.

1. Start by creating a new repository. 
    - If you are on a browser go to "your repositories" under your profile. Next click on the green button labelled "New".
    - If you are on the desktop you can create a new repository found under files (or by pressing ctrl + n).

In order to host your site on GitHub Pages you will need to be ___very specific___ with your repository name. 

2. Under repository name
    - Write your GitHub username, followed by .github.io.

    - It should look something like this ![](repositoryname.png)

3. Make sure to check off initialize the repository with a README.

4. Create the repository.

__Step 2: Adding your files__

After creating your repository you will be inside your newly created repository. Now we are going to add your resume file.

1. Under on __Add Files__ click on __Upload Files__.
2. Locate your README.md file and add it to the repository.
    - additionally you could add other files (if needed). 
3. Commit your changes.

__Step 3: Finding your Page__

Moving back to our repository we want to head into its settings.

1. Click on the __Settings__ option found in your repository. Alternatively, if you are in a smaller window it can be found in a drop down menu.

2. Click on __Pages__ found under Code and Automation.

![](pages.png)

3. Visit the site or save the link.
![](live.png)

Congratulations! You now have your own resume hosted on GitHub Pages. Feel free to share your link to others or employers you want to send your resume to. Keep in mind you can only host one GitHub Pages at a time. If you have trouble finding check out "[Why is my resume not showing up?](#frequently-asked-questions)" in the Frequently Asked Questions.

### Additional Features
------------

Maybe you think to yourself that you really dislike the layout of your markdown. It might have something to do with default font of markdown or you even wish you could change the size of your font. There are tools you can use to solve this issue like Jekyll.  


[More Resources](#more-resources)

### Authors and Acknowledgements
-------------

- Griffin LaFreniere - Markdown Techniques and Tools - Groffless

- Andrew Etter's - Modern Tecnical Writing: An Introduction to Software Documentation


### Frequently Asked Questions
-------------

__Question:__ "Why is Markdown better than a word processor?"

Markdown is better than a word processor because it is more basic than your average word processor that has tons of features which most likely will require you to take your hands of the keyboard to use your mouse. You can just type whatever you need to without having to go up and manually select a size for a title or the type of font you use. Otherwise you are losing precious time that you instead could be using to write. 

__Question:__ "Why is my resume not showing up?"

It is possible that your GitHub Pages static website is still being generated. Sometimes it takes time for GitHub Pages to update. In the meantime go do something else while waiting for it to update. It could also be possible that GitHub is down for maintenance or some other reason meaning you will have to come back to it later. Check the __Actions__ tab found under the repository to check on the process. GitHub Pages also looks for a file name such as README.md or index.md so try to check if you have written a correct file name.


### More Resources
-------------
Here are some resources for either learning markdown or as a refresher for how markdown works.

__Markdown Tutorials:__
[Markdown Tutorial](https://www.markdowntutorial.com/)
[Basic Syntax for Markdown](https://www.markdownguide.org/basic-syntax/)

__Using Jekyll:__

__Interesting Read:__
[Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

