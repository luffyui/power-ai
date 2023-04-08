# Torresix
Torresix is a fast and powerful AI for Gravitalia services ⚡️

<img src="https://media.discordapp.net/attachments/844241319165558803/1091795959949819955/image.png?width=803&height=662" />

# Detailed description

| Type  | Name          | Utility |
| :---------------: | :---------------:| :---------------:|
| Image  | [Mobilenet v2](https://arxiv.org/pdf/1704.04861.pdf)        | Classify image with precision |
|        | Grenade             | Classify image in category |
| Text   | Coco          | Classify text in category |

# Obtaining mobilenet model

In order to use the code, you'll need to get the Mobilenet model:
```
wget https://github.com/onnx/models/raw/main/vision/classification/mobilenet/model/mobilenetv2-12.onnx
```

Then, put `mobilenetv2-12.onnx` into the folder `models`
