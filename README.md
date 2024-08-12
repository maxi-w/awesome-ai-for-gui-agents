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

### UIED (UI Element Detection)
https://github.com/MulongXie/UIED

https://github.com/chenjshnn/Object-Detection-for-Graphical-User-Interface

### SeeClick

https://github.com/njucckevin/SeeClick

### ScreenAgent

CogAgent fine-tuned on the new ScreenAgent dataset.

https://github.com/niuzaisheng/ScreenAgent

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

### UISketch dataset
A dataset of 19,000 hand-drawn sketches of 21 UI element categories.

https://www.kaggle.com/datasets/vinothpandian/uisketch/data

### LightShot dataset
13,000 Screen Caps Scraped from prnt.sc.

https://www.kaggle.com/datasets/datasnaek/lightshot

### WaveUI-25k

This dataset contains 25k examples of labeled UI elements. It is a subset of a collection of ~80k preprocessed examples assembled from the following sources: WebUI, RoboFlow, GroundUI-18k.

https://huggingface.co/datasets/agentsea/wave-ui-25k

[Dataset Viewer](https://huggingface.co/spaces/agentsea/wave-ui-viz)

### GroundUI-1k & GroundUI-18k

https://huggingface.co/datasets/agent-studio/GroundUI-1K

https://huggingface.co/datasets/agent-studio/GroundUI-18K

### ScreenSpot

ScreenSpot is an evaluation benchmark for GUI grounding, comprising over 1200 instructions from iOS, Android, macOS, Windows and Web environments, along with annotated element types (Text or Icon/Widget).

https://github.com/njucckevin/SeeClick

### ScreenAgent

Collected 39 sub-task categories across 6 themes from Linux and Windows operating systems. It includes 273 complete task sessions, with 203 sessions (3005 screenshots) for training and 70 sessions (898 screenshots) for testing.

https://github.com/niuzaisheng/ScreenAgent

https://arxiv.org/abs/2402.07945

### GUI-World

A comprehensive GUI dataset comprising over 12,000 videos specifically designed to assess and improve the GUI understanding capabilities of MLLMs, spanning a range of categories and scenarios, including desktop, mobile, and extended reality (XR), and representing the first GUI-oriented instruction-tuning dataset in the video domain.

https://gui-world.github.io

https://huggingface.co/datasets/shuaishuaicdp/GUI-World

## Research Papers

[ScreenAI: A Vision-Language Model for UI and Infographics Understanding](https://arxiv.org/abs/2402.04615) (07/2024)

[ScreenQA: Large-Scale Question-Answer Pairs over Mobile App Screenshots](https://arxiv.org/abs/2209.08199) (07/2024)

[GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents](https://arxiv.org/abs/2406.10819) (06/2024)

[MUD: Towards a Large-Scale and Noise-Filtered UI Dataset for Modern Style UI Modeling](https://arxiv.org/abs/2405.07090) (05/2024)

[Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs](https://arxiv.org/abs/2404.05719) (04/2024)

[UI Semantic Group Detection: Grouping UI Elements with Similar Semantics in Mobile Graphical User Interface](https://arxiv.org/abs/2403.04984v1) (03/2024)

[AgentStudio: A Toolkit for Building General Virtual Agents](https://arxiv.org/abs/2403.17918#) (03/2024)

[SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents](https://arxiv.org/abs/2401.10935) (02/2024)

[ScreenAgent: A Vision Language Model-driven Computer Control Agent](https://arxiv.org/abs/2402.07945) (02/2024)

[CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914) (12/2023)

[From Pixels to UI Actions: Learning to Follow Instructions via Graphical User Interfaces](https://arxiv.org/abs/2306.00245) (12/2023)

[Android in the Wild: A Large-Scale Dataset for Android Device Control](https://arxiv.org/abs/2307.10088) (10/2023)

[Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding](https://arxiv.org/abs/2210.03347) (06/2023)

[Towards Better Semantic Understanding of Mobile Interfaces](https://arxiv.org/abs/2210.02663) (10/2022)

[META-GUI: Towards Multi-modal Conversational Agents on Mobile GUI](https://arxiv.org/abs/2205.11029) (05/2022)

[VUT: Versatile UI Transformer for Multi-Modal Multi-Task User Interface Modeling](https://arxiv.org/abs/2112.05692) (12/2021)

[UIBert: Learning Generic Multimodal Representations for UI Understanding](https://arxiv.org/abs/2107.13731) (07/2021)

[ActionBert: Leveraging User Actions for Semantic Understanding of User Interfaces](https://arxiv.org/abs/2012.12350) (01/2021)

[Screen Recognition: Creating Accessibility Metadata for Mobile Applications from Pixels](https://arxiv.org/abs/2101.04893) (01/2021)

[Object Detection for Graphical User Interface: Old Fashioned or Deep Learning or a Combination?](https://arxiv.org/abs/2008.05132) (09/2020)
