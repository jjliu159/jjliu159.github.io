---
layout: post
title:  "Setting Up Jekyll"
---


It was pretty annoying to set up because on M1 macbook, there's a default older ruby version. I've tried using brew to install a newer version and even tried to change the path for it in ~/.zprofile, but at the end of the day, it was riddled with more complications. 

The ruby that brew installed is a keg (not sure what it means), but I had to result in using a dedicated ruby installed (RVM) to install it, and an older version of OpenSSL 1.1. 