Fucking-Accessible-FAQ
======================

An accessible HTML/CSS/JavaScript FAQ page. See [an example](http://hypertexthero.com/faq/).

When a question is asked I want to be able to easily send a link to an answer located in a single HTML page.
The answer should also be visible with JavaScript disabled.

Deployment
---

**Not-so-geeky:**

1. Download and copy the following files into a folder called such as /faq/ on your web server: 
    - [index.html](https://raw.github.com/hypertexthero/Fucking-Accessible-FAQ/master/index.html)
    - [fafaq.css](https://raw.github.com/hypertexthero/Fucking-Accessible-FAQ/master/fafaq.css)
    - [fafaq.js](https://raw.github.com/hypertexthero/Fucking-Accessible-FAQ/master/fafaq.js)
    - [jquery.min.js](https://raw.github.com/hypertexthero/Fucking-Accessible-FAQ/master/jquery.min.js)
2. Edit index.html to add new questions and save the file 
3. You now have your own fucking accessible FAQ at YourFuckingSite.tld/faq/

**Geekier through Github (need git installed on your webserver):**

1. [Fork this project](https://github.com/hypertexthero/Fucking-Accessible-FAQ/fork_select)
2. Edit index.html to add new questions and commit your changes
3. ssh into the web server where YourFuckingSite.tld is hosted and cd into the public directory
4. `git clone git://github.com/YOURGITHUBUSERNAME/Fucking-Accessible-FAQ.git faq` **(note the Git Read-Only protocol)**
5. You now have your own fucking accessible FAQ at YourFuckingSite.tld/faq/