# Website Image Repository

This repo is intended to be a submodule to house the images for my [website](https://taks396.github.io).
While I could store these images in the main repository, that could cause the main site to become too large.
Therefore, the purpose of this repo is to act as large file storage and to use another submodule if this one gets too large as well.

All images are sorted into directories associated with the website section they belong to.
Subdirectories further sort images as needed, but the general flow of organization is as follows:
```
Image Repository
├── Core Images
│   ├── Logo.png
│   ├── Dark Mode Toggle.png
│   └── ...
├── Sidebar Section 1
│   ├── Section Content 1
│   │   ├── Content Image.png
│   │   └── ...
│   ├── Section Content 2
│   └── ...
├── Sidebar Section 2
└── ...
```
See the main repository [README](../README.md) for information on how to handle submodules.