# How to Host an Online Resume for Computer Science Students
The purpose of this README is to create a set of instructions for Computer Science Students on how-to-host an online resume while relating it to the technical writing concepts written on Andrew Etter's book [_Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=3MXM73Y2ERF8Z&dchild=1&keywords=modern+technical+writing&qid=1604025150&sprefix=modern+technical%2Caps%2C194&sr=8-1).

&nbsp;

# Audience
This README is catered towards Computer Science students who are looking to host an online resume. 

&nbsp;

# Prerequisites
 * A Github account
 * A resume written in Markdown


&nbsp;
# Tools and Principles of Technical Writing
Why host your resume online instead of keeping it as a PDF format? 
* According to Etter, hosting a file online encourages collaboration as it enables easier access for contributors. Etter also mentioned that downloaded PDFs are ticking time bombs due to its information being inaccurate as most of the time it sits on our computer with stale data. An online resume allows you to keep your information up-to-date, as well as allows you and employers to access it through the web.



&nbsp;

 ### [Github Pages](https://pages.github.com/)
Github is a version control systems that allows you to upload your projects online for other creators with the same interest to contribute, and vice versa. Under Github, Github pages allows you to host your online resume for free. According to Etter, with regards to  writing a technical documentation, Github pages allows the documentation to stay in sync with the project itself as it is located in the same repository, and it encourages developers to contribute as well. 

 Why do we use Github pages for hosting a resume? 
 1) Free-of-charge.
 2) Allows you to practice tools used in today's technical writing workforce.


 &nbsp;

 ### Lightweight Markup Language (e.g., [Markdown](https://gist.github.com/JosefJezek/5917040)) 

Lightweight markup languages have become a staple in technical writing due to it being straightforward, and is written in the way non-technical people can understand which encourages collaboration (in a human-readable way). Markdown is an infamous lightweight markup language due to its easy syntax. With this easy syntax, markdown lacks some of the advanced features present inother lighweight markup language. According to Etter, non-technical people who are knowledgable with the interest of the project are more likely to contribute, if they are given an easier way to express their creativity, hence markdown being used in today's technical writing as it has the lowest learning curve out of all the lightweight markup languages.  

&nbsp;
### A Static Site Generator (e.g., [Jekyll](https://jekyllrb.com/))
Lightweight markup languages displays the words you typed plainly. Ofcourse, you would want your resume to look presentable. This is where static site generators come in play. Etter admires static site generator because it allows speedy user access as it does not have to access databases or any server-side application. Last but not the least, static site generators allows you to design your website according to your own style.  

&nbsp;

# Steps on How-to-Host your Online Resume
This section of the README contains instructions on how to host an online resume. 

1. Create a [Github](http://github.com) account. Github allows you to host a page by making a new repository named _\<SiteTitle>\.github.io_ 

![Alt Text](https://github.com/gomezj3/gomezj3.github.io/blob/master/Creating%20a%20new%20repository.gif) 

2. Add your resume written in Markdown named _index.md_ on your Github. 
> If file is not named, _index.md_. Rename your file on your computer before uploading, or follow the steps shown on the gif.

![Alt Text](https://github.com/gomezj3/gomezj3.github.io/blob/master/Uploading%20resume%20in%20markdown.gif) 

> * In order to write your resume in Markdown, you would need a markdown editor such as Visual Studio Code, an online Markdown editor like StackEdit or you can use Github itself. 

![Alt Text](https://github.com/gomezj3/gomezj3.github.io/blob/master/Formatting%20your%20resume%20in%20markdown.gif)


3. Design your online resume by adding a Jekyll template.

![Alt Text](https://github.com/gomezj3/gomezj3.github.io/blob/master/Adding%20a%20theme%20on%20your%20repo.gif) 

4. Load your online resume by clicking on the link located on the settings and enjoy. 

![Alt Text](https://github.com/gomezj3/gomezj3.github.io/blob/master/Visiting%20your%20website.gif)

&nbsp;

Once you have uploaded your resume written in markdown. With the link from step 4, access the finish product and it should look like this:

![Alt Text](https://github.com/gomezj3/gomezj3.github.io/blob/master/Showing%20my%20resume.gif)
&nbsp;
# More Resources

* [How to use Markdown](https://gist.github.com/JosefJezek/5917040)

*  Andrew Etter's book [_Modern Technical Writing_](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=3MXM73Y2ERF8Z&dchild=1&keywords=modern+technical+writing&qid=1604025150&sprefix=modern+technical%2Caps%2C194&sr=8-1)

* [Github Pages](https://pages.github.com/)

&nbsp;
# Authors and Acknowledgements

 * __Author__: [Johnnus Gomez](https://github.com/gomezj3)
 * __Resource author__: [Josef Jezek](https://gist.github.com/JosefJezek/5917040) 
 * Group Peer-Review
   * [Connor Bean](https://github.com/williamconnorbean)
   * [Conner Kulbaski](https://github.com/ckulbaski)
   * Ayush Patel

 * Jekyll Slate-theme author: [Ben Balter](https://github.com/benbalter)
&nbsp;

# FAQs
 

1. How to make a change in your online resume? 

   Using Github's built in editor:
     1) Click on the file you want to edit located on the main repository.
     2) Click on the pen icon to edit (shown on the second gif on step 2).
     3) Save your changes by clicking on _commit changes_ to main.

2. Why is my online resume not loading?
* It might take a couple of minutes for your online resume to be displayed. Be patient.
> If problem still persists, [see Github documentation for more assistance.](https://docs.github.com/en/enterprise-server@2.20/github/working-with-github-pages)




