# Responsive video embed

It's surprisingly tricky to create a video embed page with a layout that fits inside any size iframe. However, it's necessary to do this if we want our page to be embedded in contexts where the user has no control over the HTML/CSS of the embedding page, as is often true with high-level CMSes. These kinds of CMSes often only allow the user to specify `src` URL, pointing to the embed page, but then strip away any other HTML elements around the iframe, and attributes of the iframe itself.

This repo demonstrates one approach. The video.html file and styles.css file contain the core solution. The index.html file just demonstrates that regardless of the iframe size, the video displays properly.

This solution uses only CSS, no javascript.
