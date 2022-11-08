<h1 align="center">
  <br>
  <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiXr4mw4Zj7AhX0SDABHfibBTIQFnoECBYQAQ&url=https%3A%2F%2Fwww.census.gov%2F&usg=AOvVaw3GuO0GtBqUhZ_msyq5s0RM"><img src="https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fcb96290d-34c3-47be-83c4-58105d2d9e3e%2Fdescarga.jpg?table=block&id=0a72e060-52b9-432f-93ce-d9592b8c60da&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=1600&userId=&cache=v2" alt="US Census Bureau" width="230"></a>
  <br>
  Beans Classifier with Transfer Learning
  <br>
</h1>
<h4 align="center">A Pytorch implementation of Google Vision Transformers.</h4>

<p align="center">
  <a href='https://huggingface.co/' target="_blank"><img alt='google' src='https://img.shields.io/badge/Google_Vision-Transformer-100000?style=for-the-badge&logo=google&logoColor=f4c20d&labelColor=4885ed&color=3cba54'/></a> <a href='https://huggingface.co/' target="_blank"><img alt='Hugging Face' src='https://img.shields.io/badge/Hugging-Face-100000?style=for-the-badge&logo=Hugging Face&logoColor=fcd376&labelColor=fcd41c&color=fbb30a'/></a> <a href='https://huggingface.co/' target="_blank"><img alt='pytorch' src='https://img.shields.io/badge/pytorch-100000?style=for-the-badge&logo=pytorch&logoColor=ef4c2d&labelColor=000000&color=343b44'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://scitechdaily.com/images/Mung-Bean-Sprouts.gif)

## Key Features

* This deep learning model classifies a given leaf photo by its quality. 
* Data is taken from Hugging Face and is called [vit-base-beans
https://huggingface.co/nateraw/vit-base-beans].
* We implemented transfer learning techniques. The pre-trained model is a [Vision Transformer (base-sized model)](https://huggingface.co/google/vit-base-patch16-224-in21k#vision-transformer-base-sized-model) developed by Google.



## How To Use

To clone and run this application, you will need [Git](https://git-scm.com).

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/beans-classification.git

# Go into the repository
$ cd beans-classification

# Install Jupyter Notebooks
$ pip install jupyterlab
$jupyter-lab
$pip install notebook

# Run
$jupyter notebook
```

## Credits

This model uses the following open source datasets packages:

- [Pytorch](https://scikit-learn.org/stable/)
- [🤗Beans  Dataset](https://huggingface.co/nateraw/vit-base-beans)
- [Google Vision Transformer (base-sized model)
](https://huggingface.co/google/vit-base-patch16-224-in21k)
- [Numpy](https://numpy.org/)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
