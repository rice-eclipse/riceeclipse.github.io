# Source files for riceeclip.se
riceeclip.se is Rice Eclipse's vanity domain for projects, external links, etc.

Eclipse members: To add a redirect to another page/address (Google form, webserver, etc.) use a META tag:
```
<head>
    <meta http-equiv="Refresh" content="0; URL=https://www.example.com">
</head>
```
Strictly speaking this is not the right way to go about redirects, but since we're using Github Pages that's the way it is :). Add this code to an `index.html` file in a new directory named for what you want your link to read (e.g. create the folder `/example` to make the link `riceeclip.se/example`).