---
layout: post
title:  "Netlify Q&A"
date:   2017-10-20 15:29:40
categories: netlify
---
As requested, these are my answers to the questions posed by Chris.
<!--more-->
<h4>Rank your 5 favorite, and least favorite, activities from this list:<br>
<a href="https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6" target="_blank">https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6</a></h4>
<h4>Favorite Activities</h4>
<ol>
<li>Write and maintain documentation for our software and blog posts for our website.</li>
<li>Help manage communications during a service outage</li>
<li>Respond to 60+ support requests via email or chat every day</li>
<li>Debug a customer's build using a programming language and framework that you've never seen before</li>
<li>Analyze thousands of support tickets to spot trends to improve our product</li>
</ol>

<h4>Least Favorite Activities</h4>
<ol>
<li>Find and recruit teammates for the support team</li>
<li>Deliver a talk to many people you don't know at a conference or meetup</li>
<li>Work with people to figure out if Netlify's service can solve a particular workflow or integration challenge they have</li>
<li>Create video tutorials to help teach users a specific feature or use case</li>
<li>Respond to Netlify fans on Twitter</li>
</ol>

<h4>What is your favorite thing about providing technical support?</h4>
As mentioned in my cover letter, I really live for the puzzle.  When a customer contacts support, they are usually at their wits end.  There is nothing like being able to work through their technical issue to get to the source of the problem and bring a smile back to a customer's face.

<h4>What did you think of our service during the time you used it?  Be honest!  “it sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)</h4>
The Netlify system is pretty slick, it's a straight forward system.  The push integration with GitHub is just awesome!
<br><br>
Really the only issue I had was a really minor usability one.  On the deployment pages, if you've scrolled down to look through the information, you have to scroll back to the top to find the "Back to Deploys" gray link on the black background.

<h4>Tell about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it.</h4>
After creating my Netlify account, I used the Jekyll static site generator with the one-click deploy button.  The choice to use Jekyll was a matter of simplicity.  The one-click deploy was very easy and Ruby is easy enough to understand.  I made a few adjustments in the site's settings file, and added a new post to create this page that you are reading right now.

<h4>Could you give us a suggestion to improve this test or the job posting?</h4>
I really liked the opportunity to interact with the Netlify system as part of the test.  It would be exciting to have a little more of that.

<h4>Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.</h4>
<a href="https://docs.aerialink.net/" target="_blank">https://docs.aerialink.net/</a><br>
I used this documentation extensively while working on a project.  Their breakdown and organization of the technical information and API coding samples were a lifesaver.  I also appreciated the tables and layouts to make information easier to digest.

<h4>Why do you think SSL/HTTPS is important?</h4>
When forming a good security plan, HTTPS is the absolute first line of defense.  By communicating over the internet with SSL, data transmission is encrypted and forms the foundation of securing information.

<h4>Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users</h4>
DNS configuration in and of itself is a complicated topic, even with a technical background.  For less technical internet-users, an MX record is a foreign idea, unanchored for them in any real world concepts.  They are used to accessing email and having it work, not accessing anything "behind the curtain" so to speak.
<br><br>
Another challenge is recognizing the difference between an A record and a CNAME, or when to use an IP address versus using another name.


<h4>A customer writes in saying their “site won’t build”.  Compose your best short (2-paragraph) customer-facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response.</h4>
I apologize for the difficulties you are experiencing.  Let's see if we can track this down.  Are you receiving any errors?  If so, please copy and paste the error and we will take a look.
<br><br>
If you are not receiving an error, please log into your Netlify dashboard and click sites.  Click on the site you would like to deploy, then click on Deploys in the top menu.  Click on the arrow to the right of the most recent deploy to open the log file.  Please copy and paste the information in your reply, as this will give us the most up to date information to track down the issue.

<h4>(optional/bonus) Can you set up a redirect from “/netlify/anything” to https://www.google.com/search?q=anything ?</h4>
I can, here is the link:<br>
<a href="https://hixon-jekyll.netlify.com/netlify/anything" target="_blank">https://hixon-jekyll.netlify.com/netlify/anything</a>
