---
layout: single
title:  "Scenario Driven Development"
date:   2021-08-20 16:23:47 -0500
categories: thoughts
author_profile: true
---
My software engineering journey started out creating a test automation framework for a startup in Chicago. I'll forever be grateful for this because it taught me the importance of testing and the power of autmation. Something that I don't think I'd have developed had I gone striaght to being on the product team relying on someone else to test my work.

Several years into my career, I started to get familiar with BDD, Behavior Driven Development. I implemented a BDD pattern for the first time while I was on a project for an international retailer. Our setup was typical BDD flair:


**User Story/Feature**
 - **Scenario** 1  
    - **Given** the conext     
    - **When** an action is taken      
    - **Then** the results should be {testable}


For me, this was a career changing discovery. While Unit Testing, UI Testing, and Integration Testing have always been powerful tools in my toolbox, it always felt like something was missing. 

BDD is the cross section of Unit, UI, and Integration Testing




You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
