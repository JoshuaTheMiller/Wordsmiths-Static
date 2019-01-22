A simple placeholder site for Wordsmiths.app

![Docker Automated](https://img.shields.io/docker/automated/trfc/wordsmiths-static.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/trfc/wordsmiths-static.svg)
![Docker Image Size](https://img.shields.io/microbadger/image-size/trfc/wordsmiths-static/latest.svg)

# Demo

![A screenshot](./Capture.png)

# To run

The following command makes assumptions about my current setup...

`docker pull trfc/wordsmiths-static && docker stop wordsmiths-static && docker run --name wordsmiths-static --network=wordsmithsNetwork -d --rm trfc/wordsmiths-static`
