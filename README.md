# Story Maps!
![image](https://cloud.githubusercontent.com/assets/6407796/26274400/2210fd38-3cfe-11e7-941e-aa3172367c69.png)
Use this repo to make ready to go story maps with either Leaflet or MapboxGL JS mapping libraries.

### What the difference between Leaflet and Mapbox?
* [Leaflet](http://leafletjs.com/) is a robust mapping library to load rasters tiles. It's development has been instrumental in bringing open source to maps and anyone wanting to make a map.
* [MapboxGL](https://www.mapbox.com/mapbox-gl-js/api/) is the next stage in developing web maps as it uses vector tiles and many awesome features like handling large datasets and styling maps on the client side.
* If you're interested in more, [go here](https://www.mapbox.com/help/mapbox-gl-js-fundamentals/)

### Wow that's awesome, so how can I have a map like right now?
* One of the cool things about [open source](https://opensource.org/) is that we can distribute our work with others with no license (free). If you got an amazing project you're developing, others can join in and contribute.
* One of the ways we can distribute code and works are with platforms like Github! Which is a code hosting platform for version control and collaboration, its like you sharing your Google Doc with others to edit. If someone makes some mistakes on your document and you want to return back to the version 3 days ago, you can. This is similiar. 
* There's more to Github, but in this instance we are gonna use this platform to host our maps.
* So let's make a map that will be live in a matter of minutes.

#### Steps to have github host webmaps
1. In order for you to host maps on github you need an [account](https://github.com/)
2. Log in to your account and come back to this repository (A repository aka repo is used to organize a single project, they can contain folders, files, images, datasets, pretty much anything you need for your project). In fact you are at the repository right now!
3. We need to  `fork` this repository to your account, because right now its being hosted through maptimeLA's account. Creating a `fork` is producing a personal copy of someone else's project in this case maptimeLA's. [Want to know more about forking?](https://guides.github.com/activities/forking/)
4. Fork this repo by clicking on the button labeled fork.
![Forking](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)
5. A window will appear and will ask you where you want it forked, select your account and watch it fork!
![image](https://cloud.githubusercontent.com/assets/6407796/26274288/b8970926-3cfb-11e7-8f6d-8910a70784b2.png)
6. Once complete, it should load the repo with your account name and the name of the repo. For example user `cityhubla` has forked the `storymap_tutorial` from maptimeLA
![image](https://cloud.githubusercontent.com/assets/6407796/26274301/f40cd49a-3cfb-11e7-8de3-8669213d521e.png)
7. Now we're close to getting some maps up and running but we need to change some things because they are referencing maptimeLA's repo.
8. Click on the settings button
![image](https://cloud.githubusercontent.com/assets/6407796/26274324/480da09c-3cfc-11e7-99db-828747c202a3.png)
9. In the settings, scroll down to the section labeled `Github Pages`. You will notice options for getting github to host your files (ie maps)
10. In the `Source` option, select master branch and hit save.
![image](https://cloud.githubusercontent.com/assets/6407796/26274336/800bc0d2-3cfc-11e7-9db4-d4858a2283c2.png)
11. The page will reload and scroll back down to the `Github Pages` section, you will see a note that says, `Your site is ready to be published at...' with a link. This is your link to your pages which you can hand out to friends and family.
12. Now we need copy this link and change it at the front page, know as the `readme`. Copy the link, scroll up and select the `storymap_tutorial` name next to your username. This will take you to the readme.
13. At the top of the page you will see `Demonstration Map https://maptimela.github.io/storymap` this needs to be updated with your link. To change it click on the edit button on the far right of the page and replace the link with yours and save.
14. Now you have a link to a live web map you can modify! Click on it and see a storymap of LA! (Note: It may take Github a minute or so to reflect the changes to your account, the map may not load. Give it some time and it should appear.)
15. This particular webmap `index.html` is using the mapboxGL javascript mapping library.

### To Raster or to Vector?
You will notice in your repo, two folders named `leaflet` and `mapbox`, these contain example maps using these libraries.

You can try out the maps here,
* [1_leaflet](leaflet/1_leaflet.html) | This is a very basic map, if you look at the code, you can see that just a couple lines of code can get you a map. [1_leaflet](/docs/leaflet/1_leaflet.html)

