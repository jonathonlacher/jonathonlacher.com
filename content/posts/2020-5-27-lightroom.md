---
title: "How I manage my Lightroom library"
date: 2020-05-27T13:31:34Z
---

After I bought a [mirrorless micro four thirds camera](https://www.getolympus.com/us/en/e-m10-mark-ii.html) last year, I've entered the rabbit whole of media management.

I started by shooting in JPEG and dumping the images I liked into Google Photos, simple enough, right?
After a while, for various reasons, I started shooting in RAW.
But after filling my first SD card full of RAW files, I realized I needed a way to process them.

Lightroom seems to be the default choice, so I went with that.
I know there are open source alternatives like [Darktable](https://www.darktable.org/), but I haven't invested much time into exploring it.

## Ratings

I cull my photos in waves.
I first mark for deletion any photo that I consider throwaway; such as the focus is off, or I shot a dozen photos in rapid succession and I know I won't even consider a few of them.

Then I start staring my photos.
I'll give any viable photo 1 star.
Then I'll go through all the 1 star photos and give 2 stars.
If there are enough photos, I'll repeat for 3 stars, and on rare occasions 4 stars.

## Developing

I won't touch on my editing process right now, that's a whole separate skill which I'm still learning.
But in terms of order of operations, only after culling my photos through ratings will I start developing and editing them.

## Exporting

After I've developed my photos, I'll export them to a more usable format like JPEG.
I found a great Lightroom plugin called [Jeffrey’s “Folder Publisher” Lightroom Plugin](http://regex.info/blog/lightroom-goodies/folder-publisher) which can export JPEGs in the same directory hierarchy that you store your RAW files.

For example, I store my RAW files as such:
```
raw_photos/
├── 2020-5-20/
│   ├── img223.raw
│   ├── img224.raw
│   └── img225.raw
└──2020-5-23/
    ├── img228.raw
    └── img229.raw
```

The plugin on execution will export JPEGs as follows:
```
exported_photos/
├── 2020-5-20/
│   ├── img223.jpg
│   ├── img224.jpg
│   └── img225.jpg
└──2020-5-23/
    ├── img228.jpg
    └── img229.jpg
```

I'll typically export to JPEG photos with 2 stars or higher.
At this point, they're ready for sharing.
