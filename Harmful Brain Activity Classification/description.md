# HMS - Harmful Brain Activity Classification
This project uses a Kaggle EEG dataset where EEG signals are converted into spectrogram images and classified using basic CNN models and EfficientNetB0. The models identify seizures and other harmful brain activities, with performance evaluated using Kullback–Leibler divergence.
## Dataset Information
The dataset used in this project provides information about EEG Data. It includes the following columns:

| Variable | Description |
| --- | --- |
| eeg_id | A unique identifier for the entire EEG recording. |
|eeg_sub_id  | An ID for the specific 50 second long subsample this row's labels apply to. |
|eeg_label_offset_seconds  | The time between the beginning of the consolidated EEG and this subsample. |
|spectrogram_id  | A unique identifier for the entire EEG recording. |
|spectrogram_sub_id  | An ID for the specific 10 minute subsample this row's labels apply to. |
|spectogram_label_offset_seconds | The time between the beginning of the consolidated spectrogram and this subsample. |
|label_id | An ID for this set of labels. |
|patient_id  | An ID for the patient who donated the data. |
|expert_consensus  | The consensus annotator label. Provided for convenience only. |
|[seizure/lpd/gpd/lrda/grda/other]_vote  | he count of annotator votes for a given brain activity class.|

## Objective
The objective of this project is to classify EEG spectrogram images using CNN-based models to detect seizures and other abnormal brain activities. It aims to provide a probabilistic diagnosis that reflects medical uncertainty by comparing basic CNNs and advanced models like EfficientNetB0 using KL divergence. The project also seeks to improve diagnostic speed and accuracy through automated analysis compared to traditional methods.

## Impact
This project helps reduce misdiagnosis by improving the accuracy of early neurological detection, leading to faster and more appropriate treatment for patients. It also supports neuro-specialists by streamlining the diagnostic process, enabling them to handle more cases efficiently, especially in rural and underserved areas with limited access to expert care.
