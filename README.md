# JourneyDB

[[Project Page]]() [[Paper]]() [[HuggingFace]]() [[OpenDataLab]]()

![image](./assets/jdb_teaser_small.jpg)

**JourneyDB** is a large-scale generated image understanding dataset that contains **4,429,295** high-resolution Midjourney images, annotated with corresponding **text prompt**, **image caption** and **visual question answering**.

**JourneyDB** supports **4** downstream tasks, i.e. **Prompt Inversion**, **Style Retrieval**, **Image Caption**, and **Visual Question Answering**.

## Data Samples
We provide several examples to show the contents of each instance of the dataset. For each image instance, we acquire the corresponding text prompts used to generate the images with Midjourney. Furhtermore, we employ the GPT3.5 to generate the caption and VAQ groundtruth.
![image](./assets/jdb_samples_small.jpeg)

## Benchmarks
Our dataset supports **4** downstream tasks, i.e. **Prompt Inversion**, **Style Retrieval**, **Image Caption**, and **Visual Question Answering**. We evaluate many existing methods on these tasks and provide a comprehensive benchmark. Please see our [Paper]() for more details.
<!-- 
* **Image Caption.** We show some samples from the validation set of JourneyDB captioning. The examples show the gap between the realistic images and the AI-generated images. And the general visual-language model still need some enhancement to handle generated contents.
![image](https://github.com/JourneyDB/JourneyDB/blob/main/assets/jdb_caption_small.jpg)

* **Visual Question Answering** 
We visualize some results of BLIP-2 for Multiple-Choice Visual Question Answering. The top row shows style-relevant questions and the bottom row shows content-relevant questions. It once again demonstrats the difficulty to handle the generated contents.
![image](https://github.com/JourneyDB/JourneyDB/blob/main/assets/jdb_vqa_small.jpg) -->


## JourneyDB Dataset Downloads

Please fill in the [form](https://docs.google.com/forms/d/e/1FAIpQLSeiciK0g0IA46_hFaitRhdpihhpjqt3helJNT68y-C8MfKhiQ/viewform?usp=sf_link) to acquire the download link.


## License and Citation
The JourneyDB dataset is available under the customized [Terms of Usage](https://github.com/JourneyDB/JourneyDB/blob/main/assets/Usage_Terms.md).

```
@inproceedings{
}
```
