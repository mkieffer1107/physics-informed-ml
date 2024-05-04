# physics-informed-ml
Some of my code following a [great series](https://youtube.com/playlist?list=PLMrJAkhIeNNQ0BaKuBKY43k4xMo6NSbBa&si=GRhFsR1xLx1ofiPV) by Steve Brunton + some extras 🤖


| Repo | YouTube Video | Topics |
| -- | -- | -- |
| [0](mycode/0/) | [Physics Informed Machine Learning: High Level Overview of AI and ML in Science and Engineering](https://youtu.be/JoFW2uSd3Uo?si=DuGRKbJatoM7Cyy1) | -- |
| [pinns](mycode/pinns/) | [ETH Zürich DLSC: Physics-Informed Neural Networks - Applications](https://youtu.be/IDIv92Z6Qvc?si=sOmL46aNm4AXoyV9) | -- |


---
## Set up Conda Environment

```sh
conda create --name piml python=3.11 -y
conda activate piml
pip install -r requirements.txt
```

## Delete Conda Environment

```sh
conda deactivate
conda env remove --name piml
```
