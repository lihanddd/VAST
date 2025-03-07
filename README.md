# VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset

<div align=center><img src=img/radar_compare_alldata_vast.png/ width="75%" height="75%"></div>

This is the official repository of VAST which will provide code, model checkpoint and dataset. They will be released after paper is accepted.

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-retrieval-on-activitynet)](https://paperswithcode.com/sota/video-retrieval-on-activitynet?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/text-to-audio-retrieval-on-audiocaps)](https://paperswithcode.com/sota/text-to-audio-retrieval-on-audiocaps?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/audio-captioning-on-audiocaps)](https://paperswithcode.com/sota/audio-captioning-on-audiocaps?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/text-to-audio-retrieval-on-clotho)](https://paperswithcode.com/sota/text-to-audio-retrieval-on-clotho?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/audio-captioning-on-clotho)](https://paperswithcode.com/sota/audio-captioning-on-clotho?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/image-captioning-on-coco-captions)](https://paperswithcode.com/sota/image-captioning-on-coco-captions?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-retrieval-on-didemo)](https://paperswithcode.com/sota/video-retrieval-on-didemo?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/zero-shot-video-retrieval-on-didemo)](https://paperswithcode.com/sota/zero-shot-video-retrieval-on-didemo?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/zero-shot-cross-modal-retrieval-on-flickr30k)](https://paperswithcode.com/sota/zero-shot-cross-modal-retrieval-on-flickr30k?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-retrieval-on-msr-vtt)](https://paperswithcode.com/sota/video-retrieval-on-msr-vtt?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-question-answering-on-msrvtt-qa)](https://paperswithcode.com/sota/video-question-answering-on-msrvtt-qa?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/audio-visual-question-answering-on-music-avqa)](https://paperswithcode.com/sota/audio-visual-question-answering-on-music-avqa?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/tgif-frame-on-tgif-qa)](https://paperswithcode.com/sota/tgif-frame-on-tgif-qa?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-captioning-on-tvc)](https://paperswithcode.com/sota/video-captioning-on-tvc?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/audio-visual-captioning-on-valor-32k)](https://paperswithcode.com/sota/audio-visual-captioning-on-valor-32k?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-retrieval-on-vatex)](https://paperswithcode.com/sota/video-retrieval-on-vatex?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-retrieval-on-youcook2)](https://paperswithcode.com/sota/video-retrieval-on-youcook2?p=vast-a-vision-audio-subtitle-text-omni-1)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/vast-a-vision-audio-subtitle-text-omni-1/video-captioning-on-youcook2)](https://paperswithcode.com/sota/video-captioning-on-youcook2?p=vast-a-vision-audio-subtitle-text-omni-1)

<div align=center><img src=img/VAST-model.jpg/></div>


## Citation

If you find this code useful for your research, please consider citing:


```
@article{chen2023vast,
  title={VAST: A Vision-Audio-Subtitle-Text Omni-Modality Foundation Model and Dataset},
  author={Chen, Sihan and Li, Handong and Wang, Qunbo and Zhao, Zijia and Sun, Mingzhen and Zhu, Xinxin and Liu, Jing},
  journal={arXiv preprint arXiv:2305.18500},
  year={2023}
}
```

