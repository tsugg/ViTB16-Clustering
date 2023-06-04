# ViTB16 Clustering
Exploring using K-Means clustering and cosine similarity matrices on image features from a vision transformer.

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTBiNzQ1OTdlZjY5ZTU2N2M1NzRlY2UyOGRhNTU1MGE1MWEzZTQyOCZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/HyBs6jgPS4RLHkbsC9/giphy.gif" alt="animated" />
</p>

## Requirements
* CUDA 11.7
* Python 3.10

## Getting Started 

```sh 
git clone https://github.com/tsugg/ViTB16-Clustering.git
```

```sh
cd ViTB16-Clustering
```

```sh
python3 -m venv venv
```

```sh
source venv/bin/activate
```

```sh
pip install -r requirements.txt
```

## Extra
Used visualization and cosine similarity code from here: https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/image_embeddings_analysis_part_1.ipynb \
Found ViTB16 model card on hugging face: https://huggingface.co/facebook/dino-vitb16 \
K-Means strategy found in DINO v2 paper: https://arxiv.org/pdf/2304.07193v1.pdf \
