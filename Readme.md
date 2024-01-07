# Fast pen 

A front end only codepen / jsfiddle alternative
This very tiny web page grabs code from the url, runs it in the preview pane. 
Then if you edit the code in the left page, it changes the url. 
If you want to keep your creation, bookmark it
The code is gzipped before being added to the url, which helps keeping the url to a "reasonable" size. 
You could use a shortener to share urls more easily.

# todo
- better example as default document
- link to the "homepage" at the top left, and link to help (this readme ?)
- point to the lower right corner of the textarea to let user know they can resize
- support at least tab in the editor
- see how insecure this is, but as it's on a subdomain I'm not too worried. 
- syntax highlighting.
- remove the ?src=H4sIAAAAAAAAA0 if possible