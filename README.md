# Upcoming vita games website 

This website can be found [here](http://mvaneijgen.nl/upcoming-vita-games). The website is hosted a Github.com.

![Upcoming vita games website](http://i.imgur.com/BLWDI5X.jpeg "Upcoming vita games website ")

This is a person project of my ([mvaneijgen](http://mvaneijgen.nl)) to 'up' my development skills, but mostly to create a visual pleasing and easy to find new upcoming vita games. The main goal of the project was to create a easy way for anyone to update the website, so everyone can contribute, the only thing you need is a [Github account](https://github.com/join).

## Here are the steps to add or edit a game on the website

##### Step 1.
Head over the the [embeds.yml file](https://github.com/mvaneijgen/upcoming-vita-games/blob/gh-pages/_data/games.yml) and Click the edit button (the pencil icon top right)

##### Step 2.
Copy this:

```yaml
- name: Can't use ":"
  about: Can't use ":"
  gerne: Only one gerne
  image: Upload to imgur.com and URL must contain .jpg or .gif
  gamewebsite: 
  devwebsite: 
  dateadd: Y-D-M
  releasedate: Y-D-M
  western: true OR false
  released: true OR false

```
##### Step 3.
Paste It in the document on top (on line 13) and fill out the information of the game

##### Step 4.
Fill out the "Commit changes" form and hit the "Commit changes" button

I'll will recieve your update and if everything seems fine I'll will accept the pull reqeust and your changes will be reflected on the website. 

----

## Credits
The site is build on [Jekyll](http://jekyllrb.com) and uses the [Open Theme](https://github.com/open-start/opentheme) template.
Most content I used came from http://www.neogaf.com/forum/showthread.php?t=858508 
