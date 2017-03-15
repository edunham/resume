resume
======

This is both my personal resume and an example of a DevOps Engineer's
technical resume.

The LaTeX code is licensed under the MIT license, to prevent any ambiguity
about the fact that you are welcome to copy it and use it for whatever
purposes you like. The intended purpose is to make your own resume pretty
without having to think very much about LaTeX.

See my advice at http://lug.oregonstate.edu/blog/resume/ for other technical
resume tips.

How to use
----------

To generate and view the PDF, I run ``pdflatex resume.tex && evince
resume.pdf``. You can also use the included Makefile if you prefer.

Everything before the ``\begin{document}`` configures the style and
formatting.

Your document's appearance will rarely change when you mess with indentation
in the source, but will often change if you add or remove a blank line.

How to share
------------

If you're using this repo as a template for your own resume, I recommend *not*
creating a fork. GitHub seems to intend forks to mean code which will ever get
merged back into the origin.

Instead, make an *empty* repository in your own github account called
`resume`, then:

```
yourcomputer$ git clone git@github.com:edunham/resume.git
yourcomputer$ cd resume
yourcomputer$ ed resume.tex # put your own stuff in
yourcomputer$ ed README.md # take out the stuff that only applies to edunham
yourcomputer$ git commit -am "Added my accomplishments"
yourcomputer$ git remote add me git@github.com:YOURUSERNAME/resume.git
yourcomputer$ git push me master
```

You can also `git config -e` to change the URLs so that your repo is `origin`
and my remote is `edunham`, for simplicity's sake.

This way you'll get credit on the contributions graph for changes you make.

If you just want to hack on the LaTeX code that builds the resume then PR it
back, go ahead and fork. But that's probably not your use case.

Job Search Links
================

* [We Work Remotely](https://weworkremotely.com/) has remote tech industry jobs
* [Europe Remotely](http://europeremotely.com/) weekly update on jobs for
  remoties in European time zones
* [whitetruffle](https://www.whitetruffle.com) seems to aggregate mostly
  smaller, startup-type tech opportunities
* [ziprecruiter](https://www.ziprecruiter.com/jobs) is an aggregator that
  covers categories outside of tech, but doesn't appear to have a very
  fine-grained search within categories
* [Hired](https://hired.com/signup) is a poorly-named but seemingly
  well-executed system wherein your profile goes in a marketplace for a week
  and companies sort of bid on you.
* [workintech.io](http://workintech.io/) aggregates a whole bunch of these by
  category, including diversity, geographic region, and internship
* [Hiring-Without-Whiteboards](https://github.com/poteto/hiring-without-whiteboards)
  repo lists a whole lot of companies with "unconfentional" interview
  techniques


Portland-specific job aggregators
=================================

* Meet people at events on [Calagator](http://calagator.org/).
* [pdxpipeline](http://pdxpipeline.com/jobs/) has tech and non-tech listings
* [Silicon Florist](http://siliconflorist.com/jobs/) has salaried and hourly
  tech postings
* [portlandtech](http://portlandtech.org/) has a bunch of poorly formatted
* postings, and some useful sidebar links

Interview Prep and Company Research Links
=========================================

Julia Evans's [Questions I'm Asking In
Interviews](http://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/)

Julie Pagano's [Organization information
template](http://juliepagano.com/blog/2015/08/15/job-search-retrospective/org-info-template.pdf) repeats some of Evans's questions

Liz Abinate's post on [culture
smells](http://lizabinante.com/blog/getting-hired-without-getting-burned/)

Interview guides:
* [Asana](https://asana.com/eng/interview-guide)

[Questions to ask interviewers](https://gitlab.com/doctorj/interview-questions)

Money Stuff
-----------

* [Buffer's transparency & calculator](https://open.buffer.com/transparent-salaries/)
* [Glassdoor](https://www.glassdoor.com/index.htm), obviously
* dig through [this spreadsheet](https://docs.google.com/spreadsheets/d/1-CqO6Px-0yA2421OOtJoj69_MO564XvddDYDNfHuS7A/edit#gid=999557069) if you have free time
* [#talkpay](https://twitter.com/search?q=%23talkpay)
* [Comparably](https://www.comparably.com/)


LaTeX Links
===========

https://www.overleaf.com/latex/learn/free-online-introduction-to-latex-part-1

General Resume Links
====================

* https://resumefodder.com/docs/jsonresume.html
* http://i.imgur.com/uH2Vj0D.png
* https://tisiphone.net/2016/03/17/the-worst-infosec-resume-ever/
