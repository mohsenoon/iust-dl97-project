
# IUST Deep Learning Course Project
* Project Title: "Speaker Recognition using Deep Learning"
* Course URL:  [iust-deep-learning.github.io/972/](https://iust-deep-learning.github.io/972/)

## This project is based on:

* Nagrani et al 2017, "[VoxCeleb: a large-scale speaker identification dataset](https://arxiv.org/pdf/1706.08612.pdf)"
* https://github.com/linhdvu14/vggvox-speaker-identification
* https://github.com/v-iashin/VoxCeleb


## Instructions
### Use "iust_dl97_project.ipynb" to training model from scratch or using pre-trained model as feature extractor
### You can also follow the instructions below for pre-traiend model:
* Install python3 and the required packages
* Modify `cfg/enroll_list.csv` and `cfg/test_list.csv` to point to your local enroll/test wav files
* To run evaluation: `python3 scoring.py`
* Results will be stored in `res/results.csv`. Each line has format: `[path to test wav], [correct speaker], [distance to enroll speaker 1],...[distance to enroll speaker N], [predicted speaker], [correct?]`
