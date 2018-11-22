# addendum.org-static
Static addendum.org website we use in our projects to see a representation of the final visualization in it

We have already included a container at +- line 2836 where you should either manually include the files of the app to see the end result, or better, use this in a vue package and configure it with a page property so it will inject it automatically into the page.

```
2835: <!-- APP SHOULD GO HERE -->
2836: <div id="qvvdata_app" data-location=""></div>
2837: <!-- APP SHOULD GO HERE -->
```
The `data-location=""` attribute is used internally by vue apps so we can pass it an url to some location without having to recompile the app. Generally we use this to point to our datasets.
