---
# for routes in portfolio
layout: default
permalink: /readme
title: Readme
---


# This is my old portfolio now. For up to date check the one [here](https://github.com/josuerojasrojas/josuerojasrojas.github.io)

<!-- Most importantly....

- index.html or / was build using react and the source can be found [here](https://github.com/josuerojasrojas/josuerojasrojas.github.io-react)
- this whole folder is messy which i am going to delete a lot of things later
- i need to redesign the /projects page cause it doesn't go with the aesthetic presented in the index.html (again going to delete a lot of things later)
-->

<!-- My attempt to make a generic portfolio which uses liquid templating language(jekyll), sass, CoffeeScript, and python for getting data.

I am trying to make everything as generic as possible so it can be edited easily. The easiest way is to edit the \_data folder.

If you just change the username for the python file (githubcontent.py) inside \_data file and run it then you should see a whole different projects page. (note you need a github keys for the api calls and set up environmental variables). This script gets all public projects from github along with some information. It will also get your name, profile picture,  and all languages you used in github. All this and organize in a neat yml file to be edited if needed. (note every time you run the script it will replace the previous yml file.)

The file called about me is for the home page which is work in progress (no style; need a design). The first thing is links for LinkedIn, Facebook, and Instagram which shows up in the footer. Then the content is in theory should be organize by the title and then the content, for example About Me: "I am a computer, beep bop.". Each piece would be separated into its own boxes. (again this is a work in progress so this might change)

(i need a better design but i am not a designer so do not criticizes that too harshly, or you can give me some pointers) -->

<!-- One of my main goals is to make everything usable for another user.
(this is going to be a issue opened to be worked on)
Starting in data folder githubcontent.py should be changed to the person's username
- need to seperate username from get request (and check for auth tokens exits)
- might just get more info just cause and make filter to just make yml what is wanted -->
<!-- By changing a few links it can be done.. (i might need to test it, but in theory it should work... (might need to make a separate readme on what to change to make it for another user)) -->

<!-- __Anyway to see what I am currently doing to this site check github issues for this repo. [Check it Here!](https://github.com/josuerojasrojas/josuerojasrojas.github.io/issues)__ -->

<!-- ## TODO (list for myself) EVERYTHING MOVED TO ISSUES ON GITHUB
- update this readme (forever)
- MOVE ALL PENDING ISSUES ON GITHUB SO IT CAN BE EASILY BE MANAGE !IMPORTANT
- continue design for default page
- update assets to be more universal they do not work for deeper folders
- need better fonts (google fonts?)
- navBar
  - __make icons for navbar__ (this might take a while)
    - hover and active should be different
    - should also be updated according to data(but that is later)
  - make navbar responsive
    - should hide when it is mobile and have a button to make it appear
    - from tablet and higher it should look regular
- footer
  - contact link
  - about me link?
  - should have readme link on what i am currently working on
- 404
  - should be better styled
  - center 404
- main page
  - should be about me
  - interest
- ~~main page~~ projects page
  - __change this to projects page__
  - style
    - ~~seperate content into boxed~~ partially done
      - ~~make all boxes same height~~ done
      - hide description if it doesn't fit and add a show more toggle
    - ~~align boxes in the middle~~ done
    - ~~change color scheme~~ done but need opinion of others
    - text overflow problem with long titles ie. Migration_of_Language_and_Income
    - make title a bit bigger (again text overflow problem might occur worse)
  - filter
    - need their own icon that clearly shows what it is
    - ~~submenu buttons should filter result done? NEED TO IMPLEMENT NEW METHOD TO HANDLE BOOTSTRAP COLUMNSs~~ done
      - ~~add show all~~ done
      - add sort by name, data, etc
  - maybe add images of projects (easy peasy)
    - to make it easy all information would be stored in their respective github
- ~~make script to scrape github pages to get content (also currently working on this)~~ done
  - ~~use github api just to make things easier~~ done
  - ~~organize data into json object and write it out~~ done
  - ~~use the data as content~~ done
  - ~~might move script to data folder to easily write files in right place~~ done
  - scrape preview image link (after you add them)
  - ~~get project link if there is one~~
  - get commits from this project (will be on readme or some other link rendered somewhere else)
  - might change boxes to a bit lighter color like #100f10
- test
  - display flex should have prefix???
    - test in different browsers or online if prefix is needed -->

##### Resource i used (websites and stuff)
(there might have been more but sometimes i do not keep track of everything)
- [important to know how to use](http://google.com/)
- [Jekyll Structures](https://jekyllrb.com/docs/structure/)
- [Tutorial for basic start](http://jmcglone.com/guides/github-pages/)
- [CoffeeScript on Jekyll](http://www.mattjmorrison.com/today-i-learned/2014/10/10/learned.html)
- [Jekyll use data to get other data](https://stackoverflow.com/questions/36406583/jekyll-get-specific-data-data-based-on-an-name)
- [json to yaml](https://www.npmjs.com/package/json2yaml)
- [github colors](https://github.com/ozh/github-colors/blob/master/colors.json)
- [sort with jquery](https://stackoverflow.com/questions/13490391/jquery-sort-elements-using-data-id)
- [Octicons (Github icons)](https://octicons.github.com)

__(!idea maybe have a script to log all websites....)__
