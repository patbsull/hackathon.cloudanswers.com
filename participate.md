---
title: Participate
heading: Join our open source hackathon!
description: 💻🍕💻🍕💻🍕💻🍕💻🍕💻
faq:
  - question: Are teams allowed?  Can I do it solo?
    answer: We are judging the *project* as the end product
  - question: What country do I need to reside in?
    answer: We are not limiting this to any specific countries
  - question: How will payment work?
    answer: We will use PayPal, wire transfer, or any other popular means of funds transfer
  - question: Who is sponsoring this?
    answer: a small consulting group named <a href="https://www.cloudanswers.com">CloudAnswers.com</a>
---

<strong>TLDR: Open source, online (participate anywhere) hackaton focused on making salesforce.com apps.</strong>

# HOW TO JOIN

1. Create an account on github.com (you probably already have one)

2. Fork this project site: [https://github.com/cloudanswers/hackathon.cloudanswers.com](https://github.com/cloudanswers/hackathon.cloudanswers.com)

3. Add your project to the projects page by copying the file `./_projects/example.md` to your own project name (eg `my_cool_proj.md`). Commit and open a pull request.

4. Hack and get users ~ we'll get in touch with how to share user counts in an honest way for judging.

If you're not familiar with Github we recorded this brief video of the whole process: <Br/>
[https://drive.google.com/file/d/12q6vO5khv2eFSGeWZcDqvKhLR7s5oZoQ/view](https://drive.google.com/file/d/12q6vO5khv2eFSGeWZcDqvKhLR7s5oZoQ/view)

# Timeframe

- **Start** December 1, 2018

- **Finish** December 31, 2018

- **Judging Webinar** January 2, 2018

Maybe you're finding out about this after it's already started - that's ok! If you feel like you still have enough time please join us. Some of us are still working on our ideas, after all.

# Grading

- **50%** number of beta customers (production orgs as active users)

- **50%** judging panel scores

  - **16.5%** tech chops: are you a true hacker?

  - **16.5%** polish: is it easy to understand and use, or does it have errors everywhere?

  - **16.5%** business viability: is this a real product

We typically use a scoring Google Sheet that is collaborated on by the judging panel. They review the entries together, go offline to judge and update their scores in the spreadsheet, and return to announce the winner.

# Open Source

Projects must be **open source** on Github where we can validate that commits are happening throughout the project. _This does not mean you can't charge for it._ Your license can be a pervasive license or with an added an exception that no one can use your code for commercial purposes without your permission.

{% if page.faq %}

# FAQ

<dl class="faq">
  {% for item in page.faq %}
  <div>
    <dt>{{ item.question }}</dt>
    <dd>{{ item.answer }}</dd>
  </div>
  {% endfor %}
</dl>
{% endif %}

# Help, my question wasn't answered!

Submit an issue on our [GitHub issues page (click here)](https://github.com/cloudanswers/hackathon.cloudanswers.com/issues) or send an email to hackathon(at)cloudanswers.com
