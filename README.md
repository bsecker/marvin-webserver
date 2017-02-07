# marvin-webserver
A Bootstrap-based Custom Server Web Links Page.

![Picture](http://benjamin.secker.nz/static/images/marvin.png)

**How to use:**

1. Clone the repo
2. go into _index.html_ and replace [yourip/owncloud] with the URL for your owncloud server.
3. change all the other links similarly. (shouldn't be too hard)
4. modify the webpage as you see fit

To add your own link:
```
        <div class="col-sm-3 col-xs-6">
            <div class="button-link">
                <a href="[your_ip/Router]"><img class="img-responsive" src="images/vodafone.png"></a>
                <h3 class="text-center">Router</h3>
            </div>
        </div>
 ```
Add this to the html file (before </body>), and change [your_ip/Router] to your service web UI link, and then change src="images/vodafone.png"> to correct image link.
