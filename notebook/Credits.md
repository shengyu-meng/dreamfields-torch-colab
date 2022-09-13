## Credits & Changelog
Dreamfields-3D is modified from ashawkey's [dreamfields-torch](https://github.com/ashawkey/dreamfields-torch), and its forks of [IV Pravdin](https://github.com/ivpravdin) and
[Pollinations.AI](https://github.com/pollinations), released under [MIT License](https://github.com/ashawkey/dreamfields-torch/blob/main/LICENSE).

The main improvements in this notebook & repository were done by [Shengyu Meng (Simon)](https://twitter.com/meng_shengyu), including allow visualizing training process in colab, export 360° video and 3D mesh model with vertex colour, and more augment options.This code is released under [MIT License](https://github.com/shengyu-meng/dreamfields-3D/blob/main/LICENSE)

The [original dreamfields](https://ajayj.com/dreamfields) was issued under [Apache-2.0 license](https://github.com/google-research/google-research/blob/master/LICENSE), proposed by [Jain, Ajay ](https://ajayj.com/)and [Mildenhall, Ben](https://bmild.github.io/) and[ Barron, Jonathan T.](https://jonbarron.info/) and [Abbeel, Pieter](https://people.eecs.berkeley.edu/~pabbeel/) and[ Poole, Ben](https://cs.stanford.edu/~poole/) in their paper, [Zero-Shot Text-Guided Object Generation with Dream Fields](https://arxiv.org/abs/2112.01455) published on CVPR 2022. The main different of dreamfields-torch compared with original dreamfields is,  dreamfields-torch applied the [torch version of instant-ngp](https://github.com/ashawkey/torch-ngp) to replace the [original NeRF](https://github.com/bmild/nerf) as backend, and re-write most of the codes.

The technical bases of original dreamfields are [NeRF: Neural Radiance Fields](https://github.com/bmild/nerf), released under [MIT License](https://github.com/bmild/nerf/blob/master/LICENSE), proposed by Ben Mildenhall, Pratul P. Srinivasan, Matthew Tancik, Jonathan T. Barron, Ravi Ramamoorthi, Ren Ng in their paper [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934) published on ECCV 2020, and [CLIP: Connecting Text and Images model ](https://openai.com/blog/clip/)developed by [OpenAI](https://openai.com/), released under [MIT License](https://github.com/openai/CLIP/blob/main/LICENSE).