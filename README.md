# Introduction
In task1, Contributors are required to create three headers **Introduction**, **Code** and **Contributors** in **`readme.md`**.

In task2, contributors are required to use **`include_relative`** to include contributors' md files under `_stu`, and include the last updated time using `site.time` at the bottom of the page.

In task3, contributors are required to create a new project board with any name with **Basic Kanban** template containing *"To do"*, *"In Progress"* and *"Done"*. Automations are required when setting up the project board. All other contributors need to visit **Issues** and **Pull requests** regularly.

In task4, contributors are required to modify **`code.c`**, and include the code in **`readme.md`** using GitHub shield for Travis CI

In task5, contributors are required to edit **`csci3250-2019.github.io`** in the CSCI3250 organization and add a link of our team. Then request for review from @chuckjee.

# Code
{% highlight c %}
{% include_relative code.c %}
{% endhighlight %}

[![Build Status](https://travis-ci.org/csci3250-2019/project-team-i.svg?branch=master)](https://travis-ci.org/csci3250-2019/project-team-i)

# Contributors

1. {% include_relative _stu/1155000000.md %}
2. {% include_relative _stu/1155102620.md %}
3. {% include_relative _stu/1155109132.md %}
4. {% include_relative _stu/1155106709.md %}
5. {% include_relative _stu/1155110717.md %}
6. {% include_relative _stu/1155110323.md %}
7. {% include_relative _stu/1155109498.md %}
8. {% include_relative _stu/1155112416.md %}
9. {% include_relative _stu/1155096748.md %}
10. {% include_relative _stu/1155105817.md %}
11. {% include_relative _stu/1155108479.md %}
12. {% include_relative _stu/1155107819.md %}
13. {% include_relative _stu/1155101017.md %}

# Last Update Time
{{site.time}}
