# type-samples
A place to find and contribute examples of typographic features in text, especially from non-Latin scripts.

You can use the [Visual Index](https://w3c.github.io/type-samples/) to search for samples. (Currently just a prototype.)

**I'm working on a set of guidelines for submitting images to the repo. Please check out https://github.com/w3c/type-samples/issues/21#issuecomment-281673811 before submitting stuff.**

##How this might work##

It would be useful to have place you could go to find scans of text with interesting typographic features that demonstrate how people present text content around the world.  It would be particularly useful if you could categorise, filter, and download those examples to inform work such as CSS specs, explanatory articles, etc.

Requirements:
- anyone should be able to upload samples
- anyone should be able to download the samples
- it should be possible to link to a specific sample 
- it should be possible to have a discussion about a specific sample
- we should use the same labels as for the typography index, so you can filter and select items to view.
- people should be notified, if desired, when new samples are added

After a few experiments, Github issues seemed to provide the most useful solution, but i'm open to alternatives. Github brings with it familiarity and the many useful things it just does so well.

I tried a wiki based approach, but eventually pages will get too long. Also, if you have multiple pictures in one wiki it's harder to link to one specific picture.

The one thing that would be nice, but that doesn't seem to come with Github, would be a Flickr-like album (see [an example](https://www.flickr.com/photos/ishida/albums/72157650248400402)), that allowed you to visually scan thumbnails of lots of samples at once, then zoom in to the one you want to use or leave notes on. It's a shame that Flickr is a subscription service, and that GitHub doesn't show previews of image files.

Having the samples uploaded to the repo makes it easy for anyone to download them, but it's a little painful to upload them to the repo then find the url to them so that you can link to it from the issue.  My guess is that most people will just drop a picture into an issue.

In this repo there are filters of three kinds
1 the script (not language, but the language is mentioned at the start of each issue title)
2 the feature (aligned with the typography index)
3 the type of source (eg. book, newsprint, mockup, etc.)

For example, see a list of samples about justification: https://github.com/w3c/type-samples/issues?q=is%3Aissue+is%3Aopen+label%3Ajustification

Or see all just the Arabic script samples about justification: https://github.com/w3c/type-samples/issues?utf8=%E2%9C%93&q=is%3Aissue%20is%3Aopen%20label%3Aarabic%20label%3Ajustification
