JS Segment Annotator
====================


Importing data
--------------

Prepare a JSON file that looks like the following. The required fields are
`labels` and `imageURLs`. The `annotationURLs` are for existing data and can
be omitted. Place the JSON file inside the `data/` directory.

    {
      "labels": [
        "background",
        "skin",
        "hair",
        "dress",
        "glasses",
        "jacket",
        "skirt"
      ],
      "imageURLs": [
        "data/images/1.jpg",
        "data/images/2.jpg"
      ],
      "annotationURLs": [
        "data/annotations/1.png",
        "data/annotations/2.png"
      ]
    }

Then edit `main.js` to point to this JSON file. Open a Web browser and visit
`index.html`.

Copied from "https://github.com/kyamagu/js-segment-annotator"

