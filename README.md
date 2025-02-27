# dsan6600

Attempting to track NFL players using computer vision.
Inspired by this project: https://doi.org/10.1145/3422844.3423054

## Setup
- Frames were sourced from the following videos:
  - https://www.youtube.com/watch?v=JNbk_CiwgLs
  - https://www.youtube.com/watch?v=YmAW-_f2TsA
  - https://www.youtube.com/watch?v=1N_HrZ59MZA
  - https://www.youtube.com/watch?v=HleYVZn61h4
- Due to the size of the videos and the frames resulting from them they are not included in the repository. To obtain the frames needed, download the videos and use the `video_process.ipynb` code to extract them.

## Usage
- `annotations.ipynb` contains all code needed to automatically generate the training set, including isolating the field and running the initial model to generate annotations.
- `yolo_training.ipynb` is then used to train the custom model on these generated annotations. A file containing the resultant parameters will be generated. That file could not be uploaded to this repository due to size constraints.
- `data_exploration.ipynb` has a variety of code to help look at results, as does `presentation_visuals.ipynb`. Some may not work as they rely on images that could not be uploaded due to size contstraints. 


## Results
### Pre-trained model
<img width="1192" alt="image" src="https://github.com/user-attachments/assets/3f3db9e8-9766-497d-85e9-c9a2c6a371ff" />

### Fine-tuned model
<img width="1192" alt="image" src="https://github.com/user-attachments/assets/457b5796-3647-42f5-b853-6e51d6dbcb51" />

