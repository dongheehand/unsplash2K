## Unsplash2K dataset: 2K resolution high quality images


<p align="center">
  <img width="500px" src="./figs/thumbnail.jpg">
</p>

### Description
Unsplash2K is high-resolution image dataset with 2K resolution to train Super-Resolution network. Unsplash2K dataset is crawled from [unsplash](https://unsplash.com).
Unsplash2K dataset contains 498 high-resolution images and corresponding low-resolution images which are downsampled by bicubic downsamling for x2, x4, x8 scale. Unsplash2K contains diverse contents such as animals, architectures and flowers.


### Experimental Results
We used Unsplash2K dataset for [NTIRE 2021 Learning Super-Resolution Challenge](https://github.com/andreas128/NTIRE21_Learning_SR_Space). When we add Unsplash2K to training data, Most metrics are slightly better for x4 and x8. We think this dataset is helpful for improving the performance of other model too.

For x4 SR,

|  | NCSR (DF2K) | NCSR (DF2K+Unsplask2K) |
| :--: | :--: | :--: |
| LPIPS | 0.119 | 0.118 |
| Diversity | 26.72 | 26.79 |
|LR-PSNR|50.75 |50.88|

For x8 SR,

|  | NCSR (DF2K) | NCSR (DF2K+Unsplask2K) |
| :--: | :--: | :--: |
| LPIPS | 0.278 | 0.253 |
| Diversity | 26.8 | 25.7 |
|LR-PSNR|44.55 |49.97|


### Download
Please use this link. [Unsplash2K.tar](https://drive.google.com/file/d/1IDxEUM6QL7JE8p8ms2Q-aeOAvu9Cj4vl/view?usp=sharing)

### Contact
If you have any questions about our dataset, please email to me. [son1113@snu.ac.kr](mailto:son1113@snu.ac.kr)

### Citation
If you use the Unsplah2K dataset in your research, 
We would appreciate for citing the following reference.

```BibTeX
@inproceedings{kim2021noise,
  title={Noise Conditional Flow Model for Learning the Super-Resolution},
  author={Kim, Younggeun and Son, Donghee},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops},
  year={2021}
}
```
