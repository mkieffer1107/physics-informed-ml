# physics-informed-ml
Some of my code following a [great series](https://youtube.com/playlist?list=PLMrJAkhIeNNQ0BaKuBKY43k4xMo6NSbBa&si=GRhFsR1xLx1ofiPV) by Steve Brunton + some [extras](https://youtube.com/playlist?list=PLJkYEExhe7rYY5HjpIJbgo-tDZ3bIAqAm&si=CUcEc6_Ns-aBXIK8) 🤖


| Repo | YouTube Video | Topics |
| -- | -- | -- |
| [0](mycode/0/) | [Physics Informed Machine Learning: High Level Overview of AI and ML in Science and Engineering](https://youtu.be/JoFW2uSd3Uo?si=DuGRKbJatoM7Cyy1) | pendulum equation, what is physics-informed ML |
| [1](mycode/1/) | [Choosing what to model](https://youtu.be/ARMk955pGbg?si=ahQ1RyJm7jJgdA-O) | when and when not to use ML, multi-physics interactions, autograd for optimization |
| [pinns](mycode/pinns/) | [ETH Zürich DLSC: Physics-Informed Neural Networks - Applications](https://youtu.be/IDIv92Z6Qvc?si=sOmL46aNm4AXoyV9) | PDE solving |


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
