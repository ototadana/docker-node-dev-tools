What's this ?
-------------
An image of [node.js](http://nodejs.org/) (0.11.*) runtime environment with :
*   [Grunt](http://gruntjs.com/), [Bower](http://bower.io/), [Yeoman](http://yeoman.io/)
*   [Google Chrome](https://www.google.com/chrome/), Xvfb and [OpenJDK](http://openjdk.java.net/)
    for headless testing


How to use this image
---------------------
1.  Create example scripts in `~/bin`:

    ```bash
    mkdir ~/bin
    docker run -v ~/bin:/tools --rm -it ototadana/node-dev-tools /config/init
    ```

2.  Check, edit and run them.
