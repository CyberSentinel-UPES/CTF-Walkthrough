1. Visit the url given in Challenge
    
    ![Photo 1]("https://github.com/CyberSentinel-UPES/CTF-Walkthrough/blob/9cae684371be2e5c4c048248b2857cc29f97ba91/My%20Dear%20Robot/photo_1.png")

1. Here, We can see that it's a webpage, so lets open devloper tools in your browser.
To open Devloper Tools:

    1. Press `F12`
    
    OR

    2. Do a right click and select **Inspect** Option


    ![Photo 2]("https://github.com/CyberSentinel-UPES/CTF-Walkthrough/blob/9cae684371be2e5c4c048248b2857cc29f97ba91/My%20Dear%20Robot/photo_2.png")


1. Under Elements tab we can see the whole HTML of the webpage, let's see if we find anything interesting

    ![Photo 3]("https://github.com/CyberSentinel-UPES/CTF-Walkthrough/blob/9cae684371be2e5c4c048248b2857cc29f97ba91/My%20Dear%20Robot/photo_3.png")

    ![Photo 4]("https://github.com/CyberSentinel-UPES/CTF-Walkthrough/blob/9cae684371be2e5c4c048248b2857cc29f97ba91/My%20Dear%20Robot/photo_4.png")

    There is an unsual comment, which says `I LOST MY ROBOT PLEASE HELP ME FIND IT`

    As there is the **ROBOT** word in this comment, so maybe just maybe this challege is related to `robots.txt` file

1. Basically, a robots.txt file is a web
server document that instructs search engine bots which parts of a website to crawl or avoid. For more info you visit this [link](https://moz.com/learn/seo/robotstxt)

1. Let's see if our flag is hidden inside `robots.txt` file

    ![Photo 5]("https://github.com/CyberSentinel-UPES/CTF-Walkthrough/blob/9cae684371be2e5c4c048248b2857cc29f97ba91/My%20Dear%20Robot/photo_5.png")

    At first, it looks empty but as you scroll down

    ![Photo 6]("https://github.com/CyberSentinel-UPES/CTF-Walkthrough/blob/9cae684371be2e5c4c048248b2857cc29f97ba91/My%20Dear%20Robot/photo_6.png")

    Hurray !! WE FOUND THE FLAG