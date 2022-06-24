# slack-emoji
A collection of gifs and images to create Slack and HipChat emoji with.



## Contributing

Any appropriate image that meets Slack's current upload requirements can be added to the `emoji` folder. If there is a larger resolution "original" image, that can also be added to the `high-res` folder. If the original image *is* the high res version, there is no need to add it in both places. If you do add both images, it should have the same file name in both folders (or maybe with "large" or "full" added as a suffix on the high res) so that it is easier to find.

Any image depicting people you know should have that person's permission before adding it to the repo.

To add images, or make improvements to existing images, add an issue with your request or open a PR.

### Image Guidelines

The current recommendations for emoji in the `emoji` folder are:

- Less than 128 KB
- Square when possible, at least 128px x 128px
- Transparent background when possible
- Gif's are 50 frames or less (new requirement of Slack). If you have to make your gif smaller than 128px to meet the file size, do not go smaller than 40px x 40px.
- naming should be unique (regardless of file type) - do not upload a hello.gif if hello.png already exists; pick a different name

Since Slack does change its requirements from time to time, if you notice any emoji in the `emoji` folder you want to use that now fail to upload, create an issue in this repo for it to be fixed.

### Downloading images out of Slack

If you have admin permissions to your Slack, you can export/download the uploaded emoji using the Slack API.

If you just want to download a single emoji, if it's a static image, you can right-click and copy it. If it's a GIF, go to your slack's /customize/emoji page and in your browser, right-click > Inspect the image. This should reveal the img URL in the source code. Clicking that should take you to the image file itself. Right-click > Save image as... to save it to your computer.

This won't be the originally uploaded resolution, but it should meet minimum requirements.
