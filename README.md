# Finding Duplicate Files

## Problem

Large image libraries or photo collections often contain duplicates or near-duplicates, because

* images may have been copied, renamed and saved in different folders
* images may have been modified (resizing, cropping, color adjustments)
* the image meta data (EXIF) may have been changed

## Objectives

1. Find and remove all exact duplicated (identical files) in a large image collection
2. When adding new images to an existing collection
    * discard an image if there is already a duplicate
    * put an image in the same folder as similar images
3. Find groups of near-duplicates

## References

* https://www.pythoncentral.io/finding-duplicate-files-with-python/
* https://github.com/umbertogriffo/fast-near-duplicate-image-search
* https://towardsdatascience.com/fast-near-duplicate-image-search-using-locality-sensitive-hashing-d4c16058efcb
