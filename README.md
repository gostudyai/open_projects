# Open Projects
This is a repository for the problems we've encountered in our projects. Many of them are from real applications in our business. They deserve thorough investigation and hands-on.

##  Topic 1: hand pose estimation on desktop
Human computer interation is a fundamental research topic with numerious applications in our life, such as keyboard, mouse, touchsceen, etc. Nowadays, people are trying to extend interaction between virtual world and real world, such as AR and MR. We propose a new gesture interation which can be applied in desktop games or destop study. Refer to sample videos [](). This is a localization problem similar to face landmark localization [https://arxiv.org/abs/1805.05563](https://arxiv.org/abs/1805.05563) or human pose estimation [https://arxiv.org/abs/1603.06937](https://arxiv.org/abs/1603.06937).

Goal: Localize the fingertips on desktop.

key words: accuray, running speed


## Topic 2: English and Chinese mixtured OCR
Optical character recognition has been researched for many years. Many approaches are focused on either English or Chinese recognition, while few of them consider bilingual recognition. Here we investigate English-Chinese bilingual recognition.

Modern approaches conduct OCR in two steps. First, apply object detection or segmentation approach to parse sentences/words/characters. Second, classify parsed results to strings. We refer readers to this survey[https://arxiv.org/abs/1904.01906](https://arxiv.org/abs/1904.01906).

Goal: English-Chinese bilingual recogntion (including parsing and classification)

Key words: accuracy

## Topic 3: Efficient movement detection
Movement detection is very useful in video processing. Traditional movement detection mainly relies on techniques, such as optical flow and image difference. Such approaches are vulnerable due to noise caused by lighting variation, shadow and camera quality. Refer to [https://chrome.ws.dei.polimi.it/images/e/e3/Bonarini_2006_ACM.pdf](https://chrome.ws.dei.polimi.it/images/e/e3/Bonarini_2006_ACM.pdf). Here we want to utilize deep learning for more robust solutions. Since motion detection is often used as preprocessing, efficiency is also quite important.

Goal: Motion estimation based on deep learning

Key word: accuracy, efficiency, memory, running speed
