---
title: Rails Invaders at RailsRumble
date: 2015-11-07
layout: project
highlight_menu_key: projects
image_path: /assets/images/projects/rails-invaders-at-rails-rumble/rails-invaders-logo.jpg
image_path_at2x: /assets/images/projects/rails-invaders-at-rails-rumble/rails-invaders-logo-at2x.jpg
code_link: https://github.com/welaika/rails_invaders
code_name: View the code on Github
try_the_project_link: http://railsinvaders.r15.railsrumble.com/
try_the_project_name: Try the game!
teardown_link: http://blog.railsrumble.com/2016/01/15/gem-teardown/
teardown_note: 'Rails Rumble organizer decided as usual to '
teardown_name: Teardown Heroku server instances
---
Taking part to a programming event is most of the time an interesting adventure considering that it let you meet people with the same coding passion as yours. Solving problems together in a strict time constraint it's a very challenging and entertaining experience. Everyone give his contribution to reach a common objective.

That's what happened at RailsRumble 2015 with the [friends of Welaika](https://dev.welaika.com/about-us/).
We had to produce a Ruby on Rails based application in 48 hours in team of up to 4 members.

We formed the team and proposed different projects to be implemented.

![The Team](/assets/images/projects/rails-invaders-at-rails-rumble/the-team.jpg)

We came up with the decision of making a Rails backend for a javascript browser videogame that acquires the players the points and adjust in real-time for each client connected the current ranking.

We organized the work so that some members will produce the back and other the front part of the project.

We decided to use a Javascript Game Engine called [Phaser](https://phaser.io/) to have something easy to use and we decide to start from one of the example projects (a space invaders clone) to boost up the client side development. After some customizations we came up with Rails Invaders client side code.

![the client side videogame](/assets/images/projects/rails-invaders-at-rails-rumble/rails-invaders-graphic.jpg)

For the Rails server we implemented a OAuth2 based user login, the persistance of the users and matches with Postgresql relational database and we decided to poll the current match status to the server to keep track of the matches running instant after instant.

![coding-hard](/assets/images/projects/rails-invaders-at-rails-rumble/coding-hard.jpg)

During the night I decided that I would implement also the support for [LeapMotion](https://www.leapmotion.com/) periferic to allow the user to pilot the starship with its bare hand! It was like the 4 in the morning but I was able to [pushed that feature](https://github.com/welaika/rails_invaders/commit/10861546a5e178539d72ad8fb4947a9f82511b26)

After lot of code, lot of coffee and some Heroes of the Storm games we came out with this:

<iframe width="560" height="315" src="https://www.youtube.com/embed/t7RSSw-3VsY" frameborder="0" allowfullscreen></iframe>

It has been a very satisfying weekend!

A couple of weeks later, it turned out that our Rails Invaders won the [**Third Price**](http://blog.railsrumble.com/2015/11/16/winners-announced/) of the competition!
