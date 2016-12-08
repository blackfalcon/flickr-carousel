# Carousel using Flickr API

This micro app is a single page HTML file with inline styles and Javascript resources.

### Run app locally

To run the Carousel, you can open the HTML file in any browser, or from the CLI, run a Python Simple Server using the command below within that directory.

```
$ python -m SimpleHTTPServer
```

or

```
$ python -m http.server
```

depending on your OS or Python version.

### Personalization and configuration

* For purposes of the demo, the API key has been obfuscated. To use this code and personalize with your own Flickr API key, simply delete the obfuscated variable and replace the commented  out `apiKey` variable with yours.

  ```
  var apiKey = '';
  ```

* To use another photoset from Flickr, simply replace the `album` and `albumOwner` variables.

### Example screen shot

![ImgurExample](http://i.imgur.com/m3NvpIz.png)