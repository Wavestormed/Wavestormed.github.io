# Wavestormed.github.io
Jordan's website boi.

## How-to:
This guide will teach you the basics on how to post on this here website.
This website is built on Jekyll, so remember that and if you have any issues, you can do one of them there fancy google searches to fix it.

1. To post a video, navigate to /_posts/.
2. Create a .md file under the naming convention; yyyy-mm-dd-name-of-post.md.
   * This website uses markdown for it's post format. Google markdown for formatting guidelines.
3. Put this code snippet on the top:
   * This is YAML, which is REQUIRED for Jekyll to process the post as a post.
```
---
layout: post
title: "Fiammatta"
date: 2016-10-14
section: "3D"
images:
 - "/assets/work/002_fiammatta/1.jpg"
 - "/assets/work/002_fiammatta/2.jpg"
---
```
4. Edit this header to represent the new artwork.
  * LEAVE LAYOUT ALONE!
  * title is the title of the art. Make sure it's surrounded by "".
  * date is the date the video was released.
  * section is the section keyword. Examples are 3D, Digital, and Traditional. Make sure it's surrounded by "".
  * images are the directory(s) to the artwork.

5. Write your description under said header, using markdown as formatting.
6. Commit the file, (sync if on desktop) and you should see your post in about 3 minutes.

Any questions? Email hello@yukonw.com for support.
