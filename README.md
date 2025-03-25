<div align="center" markdown> 

<img src="https://i.imgur.com/UdBujFN.png" width="250" /> <br>

# Fruits Nested Test Project  

<p align="center">

  <a href="#overview">Overview</a> •
  <a href="#description">Description</a> •
  <a href="#download">Download</a> •
  <a href="#statistics">Statistics</a> •
  <a href="#examples">Examples</a> •
  <a href="#how-to-import">How to Import</a>
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervisely.com/slack)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/fruits-nested-test)
[![views](https://app.supervisely.com/img/badges/views/supervisely-ecosystem/fruits-nested-test.png)](https://supervisely.com)
[![downloads](https://app.supervisely.com/img/badges/downloads/supervisely-ecosystem/fruits-nested-test.png)](https://supervisely.com)

</div>

## Overview

 `Fruits Nested Test` is an example project with 22 unlabeled images, 2 parent datasets and 7 nested datasets.

## Description

`Fruits Nested Test` is a small demo project for tutorial and testing purposes.

## Download

Direct download: [tar archive](https://github.com/user-attachments/files/19432605/project.zip) (21,1 MB).

## Statistics

Project contains 2 parent datasets, 7 nested datasets and 22 images in it, without annotations.

```text
📦 Fruits (Annotated)          ← The project
 ┣ 📂 Temperate                ← Main dataset #1
 ┃ ┣ 📂 ann                    ← Empty (no annotations here)
 ┃ ┣ 📂 img                    ← Empty (no images here)
 ┃ ┣ 📂 datasets               ← Where the nested datasets live
 ┃ ┃ ┣ 📂 Apple                ← Nested dataset for apples
 ┃ ┃ ┃ ┣ 📂 ann
 ┃ ┃ ┃ ┃ ┣ 📜 apple_1.jpg.json
 ┃ ┃ ┃ ┃ ┣ 📜 apple_2.jpg.json
 ┃ ┃ ┃ ┃ ┗ 📜 apple_3.jpg.json
 ┃ ┃ ┃ ┗ 📂 img
 ┃ ┃ ┃ ┃ ┣ 🖼️ apple_1.jpg
 ┃ ┃ ┃ ┃ ┣ 🖼️ apple_2.jpg
 ┃ ┃ ┃ ┃ ┗ 🖼️ apple_3.jpg
 ┃ ┃ ┗ 📂 Pear                  ← Nested dataset for pears
 ┃ ┃ ┃ ┣ 📂 ann
 ┃ ┃ ┃ ┃ ┣ 📜 pear_1.jpg.json
 ┃ ┃ ┃ ┃ ┣ 📜 pear_2.jpg.json
 ┃ ┃ ┃ ┃ ┗ 📜 pear_3.jpg.json
 ┃ ┃ ┃ ┗ 📂 img
 ┃ ┃ ┃ ┃ ┣ 🖼️ pear_1.jpg
 ┃ ┃ ┃ ┃ ┣ 🖼️ pear_2.jpg
 ┃ ┃ ┃ ┃ ┗ 🖼️ pear_3.jpg
 ┣ 📂 Tropical                 ← Main dataset #2
 ┃ ┣ 📂 ann                    ← Empty (no annotations here)
 ┃ ┣ 📂 img                    ← Empty (no images here)
 ┃ ┣ 📂 datasets               ← Where the nested datasets live
 ┃ ┃ ┣ 📂 Banana               ← Nested dataset for bananas
 ┃ ┃ ┃ ┣ 📂 ann
 ┃ ┃ ┃ ┃ ┣ 📜 banana_1.jpg.json
 ┃ ┃ ┃ ┃ ┣ 📜 banana_2.jpg.json
 ┃ ┃ ┃ ┃ ┗ 📜 banana_3.jpg.json
 ┃ ┃ ┃ ┗ 📂 img
 ┃ ┃ ┃ ┃ ┣ 🖼️ banana_1.jpg
 ┃ ┃ ┃ ┃ ┣ 🖼️ banana_2.jpg
 ┃ ┃ ┃ ┃ ┗ 🖼️ banana_3.jpg
 ┃ ┃ ┣ 📂 Lemon                ← Nested dataset for lemons
 ┃ ┃ ┃ ┣ 📂 ann
 ┃ ┃ ┃ ┃ ┣ 📜 lemon_1.jpg.json
 ┃ ┃ ┃ ┃ ┣ 📜 lemon_2.jpg.json
 ┃ ┃ ┃ ┃ ┗ 📜 lemon_3.jpg.json
 ┃ ┃ ┃ ┗ 📂 img
 ┃ ┃ ┃ ┃ ┣ 🖼️ lemon_1.jpg
 ┃ ┃ ┃ ┃ ┣ 🖼️ lemon_2.jpg
 ┃ ┃ ┃ ┃ ┗ 🖼️ lemon_3.jpg
 ┃ ┃ ┗ 📂 Mango                ← Nested dataset for mangoes
 ┃ ┃ ┃ ┣ 📂 ann
 ┃ ┃ ┃ ┃ ┣ 📜 mango_1.jpg.json
 ┃ ┃ ┃ ┃ ┣ 📜 mango_2.jpg.json
 ┃ ┃ ┃ ┃ ┗ 📜 mango_3.jpg.json
 ┃ ┃ ┃ ┗ 📂 img
 ┃ ┃ ┃ ┃ ┣ 🖼️ mango_1.jpg
 ┃ ┃ ┃ ┃ ┣ 🖼️ mango_2.jpg
 ┃ ┃ ┃ ┃ ┗ 🖼️ mango_3.jpg
 ┣ 📜 meta.json                ← Project metadata
 ┗ 📜 README.md                ← Optional readme file
```
