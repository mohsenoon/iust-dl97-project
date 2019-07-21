
# Speaker Identification based on:

* Nagrani et al 2017, "[VoxCeleb: a large-scale speaker identification dataset](https://arxiv.org/pdf/1706.08612.pdf)"
* https://github.com/linhdvu14/vggvox-speaker-identification
* https://github.com/v-iashin/VoxCeleb


## Instructions
### You can use "iust_dl97_project.ipynb" for training model from scratch or using pre-trained model as feature extractor
### You can also follow the instructions below for pre-traiend model:
* Install python3 and the required packages
* Modify `cfg/enroll_list.csv` and `cfg/test_list.csv` to point to your local enroll/test wav files
* To run evaluation: `python3 scoring.py`
* Results will be stored in `res/results.csv`. Each line has format: `[path to test wav], [correct speaker], [distance to enroll speaker 1],...[distance to enroll speaker N], [predicted speaker], [correct?]`