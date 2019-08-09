<p>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg"></a>
  <a href="https://github.com/jokenox/bloggerjs/tree/2ea81a1"><img src="https://img.shields.io/badge/latest%20ver-v0.4.0-orange.svg"></a>
</p>

**BloggerJS** is a script to modify the format of URLs in a Blogger blog. Visually creating better navigation. <br/><br/>
The script is integrated into your blog and "clean" the URLs throughout the site during navigation, removing them from the date  ```"/YYYY/MM"``` or the ```"/p"```, as appropriate, as well as the ```".html"```. Also this way it is more comfortable to share a URL, because it looks much better.<br/>

## Implementation

To implement **BloggerJS** in your blog, copy all the following code before ```</head>``` tag:
```javascript
<script src='https://chintel.github.io/bloggerjs/blogger.js'></script>
```

Once this is done, just save the changes made to your template.

### Note:
Although just copying and pasting the code, **BloggerJS** will be working, it is recommended (especially for blogs with a lot of content) to configure the script to work with the Blogger v3 API, since this is much higher in performance and speed.

## Configuration
At the beginning of the script you will find configuration variables, modifying these properties is optional. The description of each one is in the following table:

| Property	      | Default value	    | Description                                                                             |
|-----------------|-------------------|-----------------------------------------------------------------------------------------|
| postsDatePrefix | false             | Allow the date in the URLs of the posts / posts.                                        |
| accessOnly      | false             | Short URLs only serve to access the site, but not in its general operation.             |
| useApiV3        | false             | Use Blogger API v3.                                                                     |
| apiKey          | -                 | API Key for the use of Blogger API v3.                                                  |

## License
Licensed under the [MIT License](./LICENSE).<br/>
Copyright (c) 2017-2018 [Kenny Cruz](https://github.com/jokenox).
