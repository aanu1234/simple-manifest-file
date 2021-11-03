# simple-manifest-file
Manifest file is a JSON file that controls your app info, the splash screen and tells the browser about your Progressive Web App and how your app should behave on installation.


# optional

start_url: can be landing_page_url or login_url
scope: can be domain_url or directory your app is hosted
display: can be browser, minimal ui, full screen or standalone
orientation: can be portrait, landscape or any,

# how to use

Drop the manifest.json and icons directory in your root directory and edit to your app info, if you don't want to do that, you can simply create the manifest.json file and icons directory in your root directory.

Then reference or include it in your static files or (.html or .php) file in the head section

like below:

    <head>
            ------- some included files: meta, link, script, tags -------
        <link rel="manifest" href="manifest.json" />
        <!-- ios support -->
        <link rel="apple-touch-icon" href="icons/icon-72x72.png" />
        <link rel="apple-touch-icon" href="icons/icon-96x96.png" />
        <link rel="apple-touch-icon" href="icons/icon-128x128.png" />
        <link rel="apple-touch-icon" href="icons/icon-144x144.png" />
        <link rel="apple-touch-icon" href="icons/icon-152x152.png" />
        <link rel="apple-touch-icon" href="icons/icon-192x192.png" />
        <link rel="apple-touch-icon" href="icons/icon-384x384.png" />
        <link rel="apple-touch-icon" href="icons/icon-512x512.png" />
        <meta name="apple-mobile-web-app-status-bar" content="#3362d6" />
        <meta name="theme-color" content="#3362d6" />
    </head>

Feel free to drop comments! 

Opens for further modifications...
