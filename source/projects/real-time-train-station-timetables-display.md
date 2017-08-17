---
title: Real Time Train station Timetables Display.
date: 2014-11-20
layout: project
highlight_menu_key: projects
image_path: /assets/images/projects/real-time-train-station-timetables-display/train-station-timetables-display-logo.jpg
image_path_at2x: /assets/images/projects/real-time-train-station-timetables-display/train-station-timetables-display-logo-at2x.jpg
live_link: https://github.com/StefanoOrdine/station_master_interface
live_name: View the server application code
code_link: https://github.com/StefanoOrdine/station_master
code_name: View the station_master ruby gem code
try_the_project_link: http://tsds-steox.rhcloud.com/
try_the_project_name: Try it!
teardown_link:
teardown_note:
teardown_name:
---

Train Station Display Simulator è un progetto realizzato con Bootstrap per la grafica, Sinatra framework per il backend basato sul linguaggio di programmazione Ruby e la gemma Ruby station_master.

Train Station Display Simulator is a project meant to give the opportunity to consult italian train timetables in your browser as of you are standing in front of the phisical timetables display at a train station chosen by you.

It has been developed using [Bootstrap](http://getbootstrap.com/) for the frontend. It is composed by a basic 'One Page' template to let the user chose the italian train station with JQuery autocompletition feature and a page that reflects the usual times table black and yellow present in main italian stations.

![the landing page](/assets/images/projects/real-time-train-station-timetables-display/landing-page.jpg)

For the application server backend I used [Sinatra](http://www.sinatrarb.com/) a lightweight Ruby framework.
The application uses a Ruby gem [station_master](https://github.com/StefanoOrdine/station_master) that I developed to get all the times data from an unprotected api that the website [www.viaggiatreno.it](http://www.viaggiatreno.it) exposes.
