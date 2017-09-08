# HTML5学习

## 语法规则

- headlines

  <h>this is a headline</h>

- paragraph

  <p>this is a paragraph</p>

- anchor element(links)

  this is a <a href="www.codecademy.com"> link</a>

- image

  Image elements are *self-closing*, which means they do not need a closing tag.

  this is a image:<img scr="img.jpg">

> Just like websites have URLs, images on the web also have URLs. Image URLs typically end with the .jpg or .png file extension. 
>
> URL:统一资源定位符

- video(followings are copied from www.codecademy.com)

  ```
  <video width="320" height="240" controls>
    <source src="video-url.mp4" type="video/mp4">
  </video>
  ```

  > 1. `width` and `height`: Set the size of the screen that displays the video.
  > 2. `controls`: Adds play, pause and volume control.
  > 3. `source src`: Sets the URL of the video to play.
  > 4. `type`: Specifies different video formats.

- unordered list

  <ul>

  ​	<li>first list</li>

  ​	<li>second list</li>

  </ul>

- division

  <div class="main">

  ​	...

  </div>

- metadata

  > 1. `<!DOCTYPE html>`: Tells the web browser to expect an HTML document.
  > 2. `<html>...</html>`: The root of the HTML document and parent of all other HTML elements on the webpage.
  > 3. `<head>...</head>`: Enclose other metadata about the site, such as its title.
  > 4. `<title>...</title>`: Contains the site's title, which is one way users can find your site through a search engine, like Google.
  > 5. `<meta charset="utf-8"/>`: Tells the web browser which character set to use. In this case, the character set is "utf-8".

one example:

```
<!DOCTYPE html>
<html>
<head>
  <title>Ollie Bike Sharing</title>
  <meta charset="utf-8"/>
  <link rel="stylesheet" type="text/css" href="main.css">
</head>
```

