# Upgrade Your Rails Project

## Introduction

You've been working with JavaScript for the second half of the Software
Engineering course. At this point, you may feel more comfortable writing in JS,
having completed your final project in React. Don't forget about Ruby and Rails,
though!

Some of the positive feedback we've received from employers that have hired
Flatiron graduates includes the fact that students are starting out with an
understanding of both Ruby and JavaScript. Many concepts are transferrable from
one language to another - showing that you know two languages is a good
indication that you can adapt what you know to a third language.
Knowing both Ruby and JavaScript can also open up more employment opportunities,
so it is important to showcase what you know.

Updating your Rails portfolio project is a great way to do precisely this and show
that you have a variety of experiences. Below are some suggestions for
what you can do to upgrade your CLI project.

## Refactor

Just like your CLI project, you've likely improved your coding skills since you
last looked at your Rails project, even if you haven't practiced writing in Ruby
since then. Time to apply what you've learned! Read through your Rails project code
and consider some of these questions:

- **Is the code DRY? Is there any redundant content that could be reduced or
  abstracted?** Under time constraints, it is easy to forgo the [Don't Repeat
  Yourself][dry] principle. There is no due date anymore, so take some time to
  clean up any repetitive patterns in your code.

- **Can you spot and unnecessary or overly complicated code?** While learning the
  basics, it is possible to misunderstand how specific code works. Sometimes, we
  try things until something sticks. Sometimes, the moment a piece of code
  works, we move on to the next task without reconsidering what we've written.
  Now is the time to look back and find examples of this in your project.

[dry]: https://en.wikipedia.org/wiki/Don%27t_repeat_yourself

For Rails in particular, definitely review your MVC structure when refactoring.
Students often load a lot of code into their controllers. However, the
controller is really just meant to be an interface between your models and
views. It should just be handling the 'business logic' of your app - based on
the request, a **controller** will get data from a **model** and use it to
render a **view**. If there is data-related logic present, it should probably be
in a **model**.

## Finish and Add Features

Your project may meet all the requirements that were laid out at the time and be
slightly past the MVP stage. However, this does not mean it is fully developed.

Think about what features you can add to bring it to the next level. A few
suggestions specific to Rails:

- You should have some basic user authentication implemented. What features
  could be added around users? For instance, it may be helpful to provide users
  with a way to view and change their own account information like their password.
- Are there any views that could be improved? It may be that some views are
  pretty minimal in your current project - what can be added to make them look
  more appealing? What can be added to make user navigation easier within your app?
- Does your application have a consistent theme? Use the `application.html.erb`
  to build out visual content that is shared across your entire app like website
  navigation.
- If your app is hosted live, what content is needed to ensure a visitor has a
  good understanding of how it works. At a minimum, this might mean adding an
  'About' page. If your app revolves around a process that requires multiple
  steps, are all of those steps clear enough? One way to test this is to share
  your project with a non-technical friend. Can they figure out how to navigate
  it without help? Where do they get stuck, and what can be added to get them
  unstuck?

In addition to these, think about any features you weren't able to implement
originally. Are any features only partially implemented? Rails can provide a
fullstack application experience - what can you do to fully showcase your
understanding of this?

## Deploy to Heroku

The best way to showcase your Rails project is to deploy it online! Sometimes,
potential employers may utilize a non-technical recruiter to find candidates to
hire. These recruiters won't be looking at your code on GitHub. By deploying
your project, you open up the opportunity for them to explore what you've built.
Even if they don't know the technical requirements, they'll be able to play with
app features and see how developed they are.

There are a couple of options for deploying Rails projects, but the most common
way is to use [Heroku](https://www.heroku.com/). Heroku has a free hosting
that many students have utilized over the years.
[They also provide a detailed tutorial on how to get your Rails app deployed][heroku deploy].

> **Recommended:** Once you've deployed your project, make sure to do some
> quality assurance testing:
>
> - **Click every link**. Make sure there are no bad links
> - Navigate around your app in different ways. If a user does something
>   slightly unexpected, can your app handle it?
> - **Create multiple users and test your authentication**. For instance, what
>   happens if a user doesn't enter anything for a username or password?
> - **Share the app with some friends and ask them to play around with it**. You
>   might know how things are supposed to work, but giving your app to someone
>   else can identify unexpected user behaviors.
>
> Deploying your app is very helpful, but **deploying a broken app can be worse
> than not deploying anything!**

## Record a Demo Video

When your project is fully functioning and looking great, consider recording a
demonstration of how your app works. Recording a demo allows you to showcase
features you're particularly proud of. It also means you can provide context to
your application that may not be apparent from just looking at the application
itself.

A demo recording should go through the essential parts of your application. One
bonus that comes from doing this - during interviews, you will often need to
talk about your projects. If you have a project listed on your resume, assume
that you may need to explain what the project is, as well as the challenges you
faced during development. A demonstration video will force you to practice this
pitch so you'll be more comfortable when you have to do it live.

A demo recording also acts as an excellent way to introduce yourself. You can
use it to show off a bit of your personality. It also shows your ability to
communicate complex topics - a critical skill on all tech related teams.

## Conclusion

Whichever updates you choose, any time spent revisitng your portfolio projects
is time well spent. You should know the ins and outs of the projects you are
using to represent your abilities. You can't always prepare for what questions
you'll get on an interview, but being comfortable showcasing what you've already
worked on is a big plus.

[heroku deploy](https://devcenter.heroku.com/articles/getting-started-with-rails5)

