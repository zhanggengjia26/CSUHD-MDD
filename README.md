# CSUHD-MDD
# Chosun University Depression Risk Multimodal Database


Data_export/
├── README.md
├── metadata/
│   ├── subject_index.csv          # Master index: all subjects + file paths
│   ├──label_phq9_mards.csv        # Clinical depression labels
│   └──data_split.json             # Train / val / test split (seed=42)
├──action_units/
│   └── {ID}_{task}_au.csv
├── ecg/
│   └── {ID}_ecg.csv               # Raw ECG time-series (500 Hz)
├── ppg/
│   └── {ID}_ppg.csv               # Raw PPG time-series (500 Hz)
├── audio/
│   └── {ID}_reading_audio.wav     # (Reading task only)
└── emotion_text/
    └── {ID}_{task}_emotion_text.txt




