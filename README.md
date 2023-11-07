# Access this dataset

This repository is stored with XetHub.

Install the extension from https://github.com/xetdata/xet-tools/releases

Then just git clone the repository as normal.

## Mount 

Run this command to mount Flickr30k on your machine with read access. 
```
git-xet mount [repo]
```

This command is always available via the purple Access button right above this README.


# About this dataset

The Flickr30k dataset has become a standard benchmark for sentence-based image description. This paper presents Flickr30k Entities, which augments the 158k captions from Flickr30k with 244k coreference chains, linking mentions of the same entities across different captions for the same image, and associating them with 276k manually annotated bounding boxes. Such annotations are essential for continued progress in automatic image description and grounded language understanding. They enable us to define a new benchmark for localization of textual entity mentions in an image. We present a strong baseline for this task that combines an image-text embedding, detectors for common objects, a color classifier, and a bias towards selecting larger objects. While our baseline rivals in accuracy more complex state-of-the-art models, we show that its gains cannot be easily parlayed into improvements on such tasks as image-sentence retrieval, thus underlining the limitations of current methods and the need for further research.

License: [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
