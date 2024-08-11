# CLIP based application - Assignment 23
CLIP based

1. Zero shot classification
2. Image search based on text

Following notebook [assignment-23-clip.ipynb](./assignment-23-clip.ipynb) demonstrates following features of CLIP:

- Zero shot classification
- Image search based on text

We have created a directory named "sample-images", which contains following kind of images:

- a-laptop-with-gloass-bottles-on-top-of-machine.png
- bar-on-the-beach.png
- boat-on-the-beach.png
- car-crossing-zebra-crossing.png
- car-girl.png
- car-traffic-light-night.png
- car-traffic-light.png
- ducks-crossing-zebra-crossing-car-waiting.png
- elephant-crossing-road-person-on-bike.png
- glass-bottels-on-a-machine.png
- horse-camel-elephant-frame.png
- horse-camel-elephant.png
- horse-man-elephant-field.png
- horse.png
- horses-man-elephant-field.png
- hotel-on-beach-day-time.png
- hotel-on-beach-night-time.png
- hotel-room-windows-showing-beach.png
- kids-crossing-zebra-crossing.png
- swimming-pool-with-cottage.png
- swimming-ppol-near-to-beach.png
- woman-man-crossing-zebra-crossing.png

## Zero shot prediction

User can select the any image and choose classification criteria. CLIP will perform zero shot prediction. 

Top four classification will be shown as result


## Image search from the given directory
In another case user can give search phrase and it will identify top 3 images meeting those criteria


### References

- https://huggingface.co/docs/transformers/main/en/model_doc/clip
- https://github.com/mlfoundations/open_clip
- https://github.com/mlfoundations/open_clip/tree/main/docs
- https://viso.ai/deep-learning/clip-machine-learning/
- https://openai.com/index/clip/