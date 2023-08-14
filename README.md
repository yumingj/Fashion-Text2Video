# Fashion-Text2Video

**Text2Performer: Text-Driven Human Video Generation** </br>
[Yuming Jiang](https://yumingj.github.io/), [Shuai Yang](https://williamyang1991.github.io/), [Tong Liang Koh](http://haonanqiu.com/), [Wayne Wu](https://wywu.github.io/), [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/) and [Ziwei Liu](https://liuziwei7.github.io/) </br>
In International Conference on Computer Vision (ICCV), 2023.

From [MMLab@NTU](https://www.mmlab-ntu.com/index.html) affliated with S-Lab, Nanyang Technological University and Shanghai AI Laboratory.

[**[Project Page]**](https://yumingj.github.io/projects/Text2Performer.html) | [**[Paper]**](https://arxiv.org/pdf/2304.08483.pdf) | [**[Code]**](https://github.com/yumingj/Text2Performer) | [**[Demo Video]**](https://www.youtube.com/watch?v=YwhaJUk_qo0)

**Fashion-Text2Video** is a human video dataset with rich label and text annotations. It has the following properties:
1. It contains 600 high-resolution human videos from [Fashion Dataset](https://vision.cs.ubc.ca/datasets/fashion/).
2. For each video, we have annotations for motions (labels and texts).
3. For each video, we have text descriptions for clothing textures and shapes.


Fashion-Text2Video dataset can be applied to text-driven human video generation. The dataset is proposed in [Text2Performer](https://github.com/yumingj/Text2Performer).

## Download Links
You can download using the following links:

| Path | Size | Format | Description
| :--- | :---- | :---- | :----------
| [Fashion-Text2Video](https://drive.google.com/drive/folders/1gzQIAliCiNhZAsNG4Nifqpa-Wb_eYkX9?usp=sharing) | ~18 GB | - | main folder
| &boxvr;&nbsp; [Video Frames]https://drive.google.com/file/d/1zedH8lFUtZnYv_YRYI-MpHPMq68DqJj6/view?usp=sharing) | 17.27 GB | PNG | Frames from Fashion Dataset, resolution 512 x 256
| &boxvr;&nbsp; [Motion Texts](https://drive.google.com/file/d/1jmWkH0DgCyl9zsNWGWWATC2xEwjEHjvT/view?usp=sharing) | 253 KB | TXT | Texts for human motions
| &boxvr;&nbsp; [Motion Labels](https://drive.google.com/file/d/1Tq22h9-AS_kafccbpWqaIp58u7xQAF7L/view?usp=sharing) | 160 KB | TXT | Labels for human motions
| &boxvr;&nbsp; [App Texts](https://drive.google.com/file/d/1Uo3cuKyka7VjY1oyqZ7IP58rPF0NYRFy/view?usp=sharing) | 668 KB | JSON | Texts for Human Appearance
| &boxvr;&nbsp; [Motion Caption Templates](https://drive.google.com/file/d/1Zqg19tnBs_C5XbP8pIA_HTLu2V1YACbl/view?usp=sharing) | 5 KB | JSON | Motion Caption Templates

## Motion Texts
* The annotations for each video are in one txt files. The format of the annotations is as follows:

```
<start_frame_seg1> <end_frame_seg1> <text_seg1>
<start_frame_seg2> <end_frame_seg2> <text_seg2>
...
```

## Motion Labels
* We provide the source motion labels, which are manually labelled. The annotations for each video are in one txt files. The format of the annotations is as follows:

```
<start_frame_seg1> <end_frame_seg1> <label_seg1>
<start_frame_seg2> <end_frame_seg2> <label_seg2>
...
```

You can also use the [template](https://drive.google.com/file/d/1Zqg19tnBs_C5XbP8pIA_HTLu2V1YACbl/view?usp=sharing) to generate more diverse text descriptions.


## Agreement
* The Fashion-Text2Video dataset is available for non-commercial research purposes only.
* You agree not to reproduce, duplicate, copy, sell, trade, resell or exploit for any commercial purposes, any portion of the images and any portion of derived data.
* You agree not to further copy, publish or distribute any portion of the Fashion-Text2Video dataset. Except, for internal use at a single site within the same organization it is allowed to make copies of the dataset.

## Citation

If you find this dataset useful for your research and use it in your work, please consider cite the following papers:

```bibtex
@inproceedings{jiang2023text2performer,
  title={Text2Performer: Text-Driven Human Video Generation},
  author={Jiang, Yuming and Yang, Shuai and Koh, Tong Liang and Wu, Wayne and Loy, Chen Change and Liu, Ziwei},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  year={2023}
}
```
