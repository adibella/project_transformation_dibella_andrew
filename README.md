#Responsive Transformation Readme

[GitHub Link](https://github.com/adibella/project_transformation_dibella_andrew.git
)

##Resources Used
* [**The Anti-hero of CSS Layout - "display:table"**](http://colintoh.com/blog/display-table-anti-hero) : This is the site I used to gain some insight on how to solve the difficulties I was having with the footer at higher widths. I'm not sure if the is kosher with what we're supposed to be doing, but it worked for me. If there's another way to keep the footer in fixed position when using responsive design, please let me know.
* [**CSS Boiler Plate**](https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css#L107-L169) : This site, given to us by our instructor, provided the visually hidden code to hide the organizational elements in CSS used to make the site more semantic. 

##Comments

I really enjoyed this assignment. I'm still not to clear about expected indentation (I tend to overthink it). I indented everything based on the feedback from previous assignments as well as the errors that Atom gave me. Please let me know if I'm stil doing it wrong.

The sizing of the footer also gave me a bit of trouble. When the site got to a larger width the footer's background would overtake the rest of the site. After a bit of research, I found that **dispaly: table** did the trick in keeping the footer consisent and at the bottom of the page. As I noted in my explanation, I'm not sure if this is the correct and/or expected solution to this problem. Please let me know if it's not or if I missed something. 

I also was not clear about usage of floats. You said in the lectures that floats were evil (and I'm starting to agree with you) and we should avoid them wherever we can. I tried to eliminate floats as much as I could from the CSS. However, I did use floats to adjust the positon of the content and sidebar within a media query. I also kept the flots for the blog post authors and dates. I chose to do this because I thought that these elements did not play a huge role in the overall layout of the site and these floats wouldn't have a major effect outside of the article of the the blog post. I wasn't sure if this is the right solution, and if it's not please let me know what the right one is.

Finally, my commits are probably way to disorganize. I tried to commit as much as possible, but there were a few times I ended up backtracking and recommiting. There's a general sequence to it, but there are a few random commits that are just me adding in things/steps that I missed. I apologize for the disorganization and any confusion it may cause.

Thanks for your feedback and efforts!