# Object Detection with YOLOx

## Getting Started

Clone this repo and install `requirements.txt` in a `Python>=3.7.0` environment, 
including `PyTorch>=1.7`. The models and datasets download automatically from the
latest YOLOx release.

```bash
git clone https://github.com/Megvii-BaseDetection/YOLOX
cd YOLOX
pip install -r requirements.txt
```

Alternatively, use the links provided below to open them in Google Colab.

## Training on Custom Data

All the notebooks in this repo make use of the @Megvii-BaseDetection scripts for training 
YOLOx models on custom data.

<table class="tg">
  <tr>
    <th class="tg-yw4l"><b>Name</b></th>
    <th class="tg-yw4l"><b>Dataset</b></th>
    <th class="tg-yw4l"><b>Description</b></th>    
    <th class="tg-yw4l"><b>Notebook</b></th>
  </tr>
  
  <tr>
    <td class="tg-yw4l">Demo COTS (Kaggle)</td>
    <td class="tg-yw4l"><a href="https://www.kaggle.com/competitions/tensorflow-great-barrier-reef/data">COTS</a></td>    
    <td class="tg-yw4l">Detect starfish in real-time by training a model on underwater videos of coral reefs</td>
    <td class="tg-yw4l"><a href="https://colab.research.google.com/github/datasith/ds-experiments-yolox/blob/main/demo_kaggle_cots.ipynb">
      <img src="https://colab.research.google.com/assets/colab-badge.svg" width="" >
    </a></td>
  </tr>
  
</table>

## Errata

## Datasets

I'm using a few datasets to train on. This list will be updated with each added one.

- COTS (coral-eating crown-of-thorns starfish [COTS])

---

🐞 If you find any bugs or have any questions regarding these notebooks, please open an issue. I'll address it as soon as I can. 

🐦 Reach out on [Twitter](https://twitter.com/datasith) if you have any questions. 

🔗 Please cite the following if you use the code examples in your research:
```bibtex
@misc{zabala2022ml,
  author    = {Zabala, Francisco},
  title     = {DS Experiments YOLOx},
  journal   = {GitHub},
  year      = {2022},
  url       = {https://github.com/datasith/ds-experiments-yolox},
}
```
