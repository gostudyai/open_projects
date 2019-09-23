# open_projects
This is repository for problems we've encountered in our projects. They share similar features with popular research topics in computer vision and deep learning, but not exactly the same. Many of them are extracted from real applications in our daily life. They deserve thorough investigation and hands-on.

##  Topic 1: hand pose estimation on desktop
Human computer interation is a fundamental research topic with numerious applications in our life, such as keyboard, mouse, touchsceen, etc. Keyboard and mouse enable us to interact in virtual world and touchscreen extends this virtual-world experience. Nowadays, people are trying to investigate interaction between virtual world and real world, like AR and MR. We propose a new gesture interation which can be applied in desktop games or study.

Goal: Localize the fingertips in sample videos. [link]
key words: accuray, running speed

This is a localization problem similar to face landmark localization [link] or human pose estimation [link]. Various approaches are also proposed in [link]. 



## Topic 2: English and Chinese mixtured OCR
Optical character recognition has been researched for many years. Many approaches are focused on English or Chinese recognition, while few of them consider bi-lingual recognition. Here we investigate english-chinese bi-lingual recognition.

Modern approaches conduct OCR in two steps. First, apply object detection or segmentation approach to parse sentences/words/characters. Second, classify parsed results to strings. We refer readers to this survey[link].

Goal: English-Chinese bilingual recogntion (including parsing and classification)
Key words: accuracy

## Topic 3: Efficient movement detection
Movement detection is very useful in video processing. Traditional movement detection mainly relies on techniques, such as optical flow and image difference. Such approaches are vulnerable due to noise caused by lighting variation, shadow and camera quality. Here we want to utilize deep learning for more robust solutions. Since motion detection is often used as preprocessing step, efficiency is also important.

Goal: Motion estimation based on deep learning
Key word: accuracy, efficiency, memory, running speed
