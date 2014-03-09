---
layout: post
title:  "Welcome to Jekyll!"
date:   2014-03-09 13:19:47
categories: jekyll update
---

When getting started with Web Development spending a lot of time on setting up one's development environment can be a lengthy and sometimes frustrating experience.

This is why I propose one stack of technologies and explain in detail how to get going with these:

RVM
Bundler
Rails 4
Ruby 2.1.0
Postgres (the database)
haml
Sass
Git (repository hosting on Github)
Sublime Text 3
Rspec (for Unit Testing)

Setting up Sublime:

http://t3n.de/news/sublime-text-theme-532189/

I've been hearing very good things about Intellj, an IDE - platform. Will check it out eventually and let you know about it. It powers Google's upcoming "Android Studio" and is supposed to do wonders in Rails.

Another text editor that is often mentioned is Vim (Vi improved) this open Source tool is very complex and has a steep learning curve. I'll not spend significant time on it until I've done much more web development myself (in order to get a marginal improvement in productivity from switching from Sublime to Vim I have to have some skills in the first place)

To make it short: All these decicions are important, especially if you work on a "real" project which you might want transform to a startup. But to get up and running and let the actual learning take place, detailed analysis in the above mentioned areas (and countless more) is not the best use of your time. I would like to enable you to build things as quickly as possible. After all this is what development is actually about. This is the fascinating, liberating and fun part.

For the life of me I was not able to install Ruby with Rbenv (i should not have messed with my .bashrc and .bash_profile and .profile files before) I've now read a lot about that topic and have been convinced that Rbenv is the better solution because it works better with bundler. Also, it adheres to the UNIX principle of only fulfilling one task.

Install rbenv by following the instructions here:

https://github.com/sstephenson/rbenv#readme

also, install ruby build for rbenv

https://github.com/sstephenson/ruby-build#readme

If it works for you, fine if not here's how to install RVM on Ubuntu:

Another thing I might try is to install rbenv and install ruby from source in case the problem was there. I might also have an understanding problem. Since RubyGems is already integrated in RVM, does that mean that I need RubyGems in addition to Rbenv? How does that relate to Bundler?


Create a folder in which you would like to do your project with:

<code>mkdir nameOfTheFolder</code>

In the commandline, 
to display the directory you're currently in use:

<code>pwd</code>
with <code>cd</code> you can <b>c</b>hange <b>d</b>irectories.

For auto  -completion of the path you want to switch to press "Tab" twice.

Within the directory (in my case it is /home/max/skillbuilding/rails/) use <code>rails new 'name of your app'</code> to let Rails do its magic and build your app.

To understand the different parts rails created you can head over to Rails Guides and take a look:

http://guides.rubyonrails.org/getting_started.html

Bundler:

What is bundler, why is it needed?
How to install bundler?

It does not look like Octopress is still getting support, this is why I will now look at Jekyll directly.

Another project that seems very promising is Sinatra, which is much more lightweight than Rails:

http://www.sinatrarb.com/

Worth checking out!


Example Code with Syntax Highlighting:

{% highlight ruby linenos%}
def foo
	puts 'Examplecode'
end
{% endhighlight %}

You can look up more highlighting tags (for more languages that is) in the Rouge wiki:

https://github.com/jayferd/rouge/wiki/List-of-supported-languages-and-lexers

the linenos attribute refers to the line numbers of the code.

Stylesheets for syntax highlighting

In order for the highlighting to show up, you’ll need to include a highlighting stylesheet. For an example stylesheet you can look at syntax.css. These are the same styles as used by GitHub and you are free to use them for your own site. If you use linenos, you might want to include an additional CSS class definition for the .lineno class in syntax.css to distinguish the line numbers from the highlighted code.

