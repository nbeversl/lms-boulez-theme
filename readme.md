# "Boulez" Frontend for Logitech Media Server - Theme

Boulez is a modern frontend that brings the speed, extensibility, and usability of a single-page React app to the legacy of Logitech's beloved open source media server.

This repository is a full LMS theme that includes a built "Boulez".
If you are looking for the source code for Boulez, go to https://github.com/nbeversl/lms-boulez. 

## Contents

This repository is a fork of the "Default" theme for Logitech Media Server, provided as provided as a convenience for installing the Boulez frontend. It is identical to the contents of [Default](https://github.com/Logitech/slimserver/tree/public/8.0/HTML/Default), except:

- index.html is modified to provide a container to bootstrap the React app
- unneeded HTML and PERL templating is stripped from the landing page
- the addition of `main.js`, the React app itself
- a few needed icons and graphics in the `/html` folder

The rest of the Default theme is intact so you can still access the old settings panels without having to switch themes.

## Installation

Download or clone this respository and put the folder into the `HTML` directory of your LMS server. The folder will depend on your operating system. See this page for full information: http://wiki.slimdevices.com/index.php/Logitech_Media_Server_file_locations

In the settings panel of the old web interface under Interface, choose Web Interface: Boulez. 

Refresh the page and enjoy.

The frontend will run faster as your browser caches images and assets.

Boulez is named after the French composer and conductor [Pierre Boulez](https://nyphil.org/about-us/artists/pierre-boulez-1).
