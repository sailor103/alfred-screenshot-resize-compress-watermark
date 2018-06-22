# Alfred-screenshot-resize-watermark

An alfred workflow to take a screenshot manually, after the screenshot is generated, a process is actived by ImageMagick to rezise, compress, add the watermark. At last, the new screenshot would be copied to the system's clipboard.

# Required tools and operations

* ImageMagick

[ImageMagick](https://www.imagemagick.org/) is required to process the screenshots. You can install it by homebrew or other package managers.

* Default directory

~/Pictures/screenshots should be existed before use the workflow.

# Shortcut key

`command + shift + 0` take the screenshot with watermark.

`command + shift + 9` take the screenshot without watermark.

