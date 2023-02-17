TODO: Put raw landmarks here.

### How to prepare dataset

1. Download a pre-trained model from [Model Zoo](#model-zoo) and put the model into the *`$TCN_LIPREADING_ROOT/models/`* folder.

2. For audio-only experiments, please pre-process audio waveforms using the script [extract_audio_from_video.py](./preprocessing/extract_audio_from_video.py) in the [preprocessing](./preprocessing) folder and save them to *`$TCN_LIPREADING_ROOT/datasets/audio_data/`*.

3. For VSR benchmarks reported in **Table 1**, please download our pre-computed landmarks from [GoogleDrive](https://bit.ly/3lEvDjs) or [BaiduDrive](https://bit.ly/3InhIYQ) (key: m00k) and unzip them to *`$TCN_LIPREADING_ROOT/landmarks/`* folder. please pre-process mouth ROIs using the script [crop_mouth_from_video.py](./preprocessing/crop_mouth_from_video.py) in the [preprocessing](./preprocessing) folder and save them to *`$TCN_LIPREADING_ROOT/datasets/visual_data/`*.

4. For VSR benchmarks reported in **Table 2**, please download our pre-computed landmarks from [GoogleDrive](https://bit.ly/3huI1P5) or [BaiduDrive](https://bit.ly/2YIg8um) (key: kumy) and unzip them to *`$TCN_LIPREADING_ROOT/landmarks/`* folder. please pre-process mouth ROIs using the script [crop_mouth_from_video.py](./legacy_preprocessing/crop_mouth_from_video.py) in the [legacy_preprocessing](./legacy_preprocessing) folder and save them to *`$TCN_LIPREADING_ROOT/datasets/visual_data/`*.
