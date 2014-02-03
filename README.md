Pico-front-page
===============

Define the content you want to see on your front-page

Plugin for [Pico](http://pico.dev7studios.com/), also see their Github Repository [https://github.com/gilbitron/Pico](https://github.com/gilbitron/Pico)

We use this plugin to show content on example.com that is also available (or because of content organization) under example.com/my/content

Keep in mind, you'll generate "duplicate content" - but hey, it's only one page :-)


Installation
------------
    
copy the php file in your plugin folder

Setup
-----
Add the following line to your ```config.php```

    $config['front_page'] = "/my/content";
    
And the plugin shows the content of ```/content/my/content.md``` on the front-page.
    
You might also use 

    $config['front_page'] = "/my";
    
Then we'll use content in ```/content/my/index.md```
