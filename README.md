# Forest-Running

This website is built using HTML and CSS to create a Forest of Dean running guide providing the user a choice of different running start points and run type with a recommended rough route to start their eploration of the beautiful Forest of Dean.

It is designed to attract new runners to the area and encourage local runners to explore new routes with the use of spectacular images that can be found on each particular run. It does not not give the user an exact route to follow as I want to encourage runners to explore and enjoy the challenge of trying to find the view shown on the website. They can then share this on various social media services which are linked on this website to drive running tourism in the Forest of Dean.

## Features

- __Welcome Image and Header__

  - This image and Header title welcomes the user to the website and remains there across all five pages. It provides a clear site title so the user knows what the topic of this site is straight away and also a bold visual image of one of the great views that can be found when running in the Forest of Dean. Inviting them to explore the website and the Forest of Dean further.
        
  ![Header image](https://github.com/TheRealBond/Portfolio-1-Forest-Running/blob/main/assets/images/header.png?raw=true)

- __Navigation Bar__ 
    
    - Provides the user site navigation via a bar with links to each internal page for fast intuitive movement around all pages. This encourages them to look in to all the types of runs that they can enjoy and what other views they may be able to find.
        
   ![navigation bar image](https://github.com/TheRealBond/Portfolio-1-Forest-Running/blob/main/assets/images/navigationbar.png?raw=true)

- __Run type selection section__
    
    - Allows the user to choose what type of run they wish to go on that when clicked takes them to the relevant internal page with more information providing a starting point, a recommended route and a glimpse of the type of views they may be able enjoy on that route.
        
 ![image of run selector section](https://github.com/TheRealBond/Portfolio-1-Forest-Running/blob/main/assets/images/run-selector.png?raw=true)

- __Image of forest view__
        
    - An image to engage the user with another beautiful view of the area they can choose to explore shown on the home page which then displays a new view that they can find depending which run type they choose and are currently viewing that runs page.

    ![image of running view](https://github.com/TheRealBond/Portfolio-1-Forest-Running/blob/main/assets/images/running-view-feature.png?raw=true)

- __Social and Google Maps links with weather widget__
    - Links provided to the user so that they can share their run with people to encourage the growth of running tourism in the Forest of Dean. Google Maps link also provided so that the user can find out how they can get to the area and their chosen start point with a weather widget showing the local forecast to allow them to plan their run and kit choice.
        
- __Youtube iframe__
    - One of the best running songs to help motivate the user to get out and run linked to youtube video so they can control and listen when they want as they browse the website.

### Testing:

    General 
            - Website has been tested to work on different browsers: Chrome, Safari, Edge.
            - All text is easily readable and layed out in a logical way to help navigation.
            - All links internal and external are functioning correctly.
            - Wesbite is reponsive and all functions work across a variety of screen sizes.

    Bugs:
        - When Website was first deployed via GitHub Pages no images were being loaded.
        - This has now been fixed by adding . before the / on the file path for all images as shown here (src="./assets/images/forest-sunny-view.jpg")

    Unfixed Bugs:
        -None

    Validation testing:

    HTML through official [W3C validator](https://validator.w3.org/) returned: No errors 

    CSS through official [W3C validator jigsaw](https://jigsaw.w3.org/css-validator/) returned: No errors

    Accessibility through Lighthouse in devtools returned:
    
 ![Lighthouse test result image](https://github.com/TheRealBond/Portfolio-1-Forest-Running/blob/main/assets/images/lighthouse-test-result.png?raw=true)

### Deployment:

    Deployed to GitHub Pages via the following steps:
        Create the site on GitPod from the Repository (Portfolio-1-Forest-Running
        ) on GitHub. From the Repository go to the settings tab. Select the Pages section from the Code and automation section. Select the Main branch as the source, /(root) and click save. This then published the site with all updates being pushed from GitPod using the Git Push terminal command.

    [link to live running site:](https://therealbond.github.io/Portfolio-1-Forest-Running/)

### Credits:

   Content 

    - Icons used for social media links in the Share your run section with others and the runner icon in the run type selection section are provided by [Font Awesome](https://fontawesome.com/)

    - [Weather widget](https://weatherwidget.io/) provided a great item to add to the website to provide weather information that would help the user plan their run, code used: 
    ``` <a class="weatherwidget-io" href="https://forecast7.com/en/51d79n2d62/coleford/" data-label_1="COLEFORD" data-label_2="WEATHER" data-theme="original" >COLEFORD WEATHER</a>
    <script>
    !function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
    </script>
    ```
    - Youtube iframe to show one of my favourite running songs, code used:
    ```
    <iframe width="560" height="315" src="https://www.youtube.com/embed/AOBs8dU4Pb8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    ```

   Media:
   - All images used have been provided by myself.

