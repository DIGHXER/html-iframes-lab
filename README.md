# HTML Iframe Lab

## Learning Goals

- Incorporate an embedded Google map from scratch
- Reinforce our understanding of iframes

## Introduction

The `iframe` element displays an entire HTML file inside itself, allowing one
HTML page to be contained within another. Before JavaScript became widely used
in websites, _anytime_ a user clicked on a link, the entire page would refresh.

The `iframe` tag can be used to reload specific parts of a page without changing
others, providing a better user experience. For example, when a navigation link
was clicked, the whole page would not reload: instead only the iframe portion.

With JavaScript, HTML content can be added and removed programmatically without
needing a refresh. This replaced the need for the `iframe` tag in many websites.

Still, there are some specific uses where `iframe` remains valuable. One
example: embedded maps. Embedded maps are a simple option for websites that need
a custom map (i.e. contact pages for businesses). An `iframe` is used to contain
the entire interactive map page within a websites. While using an `iframe`, wehttps://www.google.com/maps
do not need to write our own JavaScript and we can incorporate all that
pre-built functionality neatly.

In this lab, we will add an iframe to our existing HTML contact form for
Walkies, Inc. To do this, we will be incorporating an embedded map similar to
those we see on business websites.

## Incorporate an Embedded Google Map from Scratch

Before we can get to writing HTML, we need to get a map to embed within an
iframe.

In your browser, head to
[https://www.google.com/maps]() and search for a
general location. For instance, a great place to walk dogs in New York City is
`Prospect Park, Brooklyn, NY`.

Now, click the menu icon located at the top left of the screen and select
**Share or embed map**.

![Share or Embed Map](https://curriculum-content.s3.amazonaws.com/html-iframes/share-or-embed-map-prospect.png)

Then click the **Embed map** tab.

Google provides the entire iframe tag, but we will add some additional
attributes manually. Highlight the iframe embed code and copy it to your
clipboard. In `index.html` paste the code snippet.

## Reinforce Our Understanding of Iframes

We've already got a basic `iframe` from Google. To pass all the tests, we'll
need to add the following attributes:

- Edit/Add a `width` attribute set to "100%"
- Edit/Add a `height` attribute set to "400px"
- Change the `frameborder` attribute to "1"

Run `learn lest` to test your work.

## Conclusion

The `iframe` element allows us to load another HTML page inside our own HTML
page. It is like looking through a window from _our_ page into another page
displaying a Google Map.

While many uses of `iframe` tags were replaced with JavaScript, they still
prove valuable in specific cases.

## Resources

- [Google Maps developer documentation](https://developers.google.com/maps/documentation/embed/guide)
