[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

# AI for the Graphical User Interface Domain

This list features awesome projects, models and datasets around AI on graphical user interfaces.

## Contents

* [Models](#Models)
* [Datasets](#Datasets)
* [Research Papers](#Research-Papers)

## Models

### CogAgent
https://github.com/THUDM/CogVLM

### Fuyu-8B
https://www.adept.ai/blog/fuyu-8b

https://huggingface.co/adept/fuyu-8b

### Pix2Struct
https://github.com/google-research/pix2struct

https://huggingface.co/google/pix2struct-base

### Pix2Act
https://github.com/google-deepmind/pix2act

## Datasets

### Rico: A Mobile App Dataset for Building Data-Driven Design Applications
http://www.interactionmining.org/rico.html

### UI understanding datasets for UIBert
https://github.com/google-research-datasets/uibert

Two datasets that are extended from the public Rico dataset, which contains 72k mobile app UI data. They add two different types of annotations to these UIs.


1. In AppSim, each datapoint contains two UIs of similar category and the annotation of two semantically similar UI elements on them, such as a “Menu” buttons that appear on two UIs.
2. In RefExp, each datapoint contains a UI and a referring expression of a UI element on it, such as “Red button on the top”.

### META-GUI

META-GUI is a dataset for training a Multi-modal convErsaTional Agent on mobile GUI. It consists of 1125 dialogues, 4684 dialogue turns and 18337 data points in total. Each data point contains screenshot history, action history, dialogue history, items appeared on the current screen and actions to be performed.

https://x-lance.github.io/META-GUI-Leaderboard/

https://huggingface.co/datasets/X-LANCE/META-GUI

https://github.com/X-LANCE/META-GUI-baseline

### Android in the Wild (AitW)

Android in the Wild (AitW) is a large-scale dataset for mobile device control that contains human-collected demonstrations of natural language instructions, user interface (UI) screens, and actions for a variety of human tasks.

https://github.com/google-research/google-research/tree/master/android_in_the_wild

### RICO Semantics

The RICO Semantics dataset consists of around 500k human annotations on the RICO dataset identifying various icons based on their shapes and semantics, and associations between selected general UI elements (like icons, form fields, radio buttons, text inputs) and their text labels. The annotations also include human annotated bounding boxes which are more accurate and have a greater coverage of UI elements than using bounding boxes from the view hierarchy.

https://github.com/google-research-datasets/rico_semantics

### ScreenQA datasets

The dataset contains ~86K questions and answers for ~35K screenshots from the public Rico dataset.

https://github.com/google-research-datasets/screen_qa

## Research Papers

[UIBert: Learning Generic Multimodal Representations for UI Understanding](https://arxiv.org/abs/2107.13731) (07/2021)

[Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding](https://arxiv.org/abs/2210.03347) (06/2023)

[Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719) (04/2024)

[VUT: Versatile UI Transformer for Multi-Modal Multi-Task User Interface Modeling](https://arxiv.org/abs/2112.05692) (12/2021)

[META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI](https://arxiv.org/abs/2205.11029) (05/2022)

[From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces](https://arxiv.org/abs/2306.00245) (12/2023)

[Android in the Wild: A Large-Scale Dataset for Android Device Control](https://arxiv.org/abs/2307.10088) (10/2023)

[Towards Better Semantic Understanding of Mobile Interfaces](https://arxiv.org/abs/2210.02663) (10/2022)

[ScreenQA: Large-Scale Question-Answer Pairs over Mobile App Screenshots](https://arxiv.org/abs/2209.08199) (07/2024)

[ScreenAI: A Vision-Language Model for UI and Infographics Understanding](https://arxiv.org/abs/2402.04615) (07/2024)

[CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914) (12/2023)

[ActionBert: Leveraging User Actions for Semantic Understanding of User Interfaces](https://arxiv.org/abs/2012.12350) (01/2021)

[Screen Recognition: Creating Accessibility Metadata for Mobile Applications from Pixels](https://arxiv.org/abs/2101.04893) (01/2021)
