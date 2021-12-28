This script is a utility to download [Mozilla Common Voice Dataset](https://commonvoice.mozilla.org/en/datasets). It handles everthing from downloading to creating manifest files.
Particularly useful for creating files for nemo_models

Attention ! - Requires sox with mp3 support : Install as : 

Usage: 
Open cmd and navigated to script folder using `cd script_folder` and enter: 
```
python get_commonvoice_data7.0.py
```

Advanced Usage Guide
```
usage: get_commonvoice_data7.0.py [-h] [--data_root DATA_ROOT]
                                  [--manifest_dir MANIFEST_DIR]
                                  [--num_workers NUM_WORKERS]
                                  [--sample_rate SAMPLE_RATE]
                                  [--files_to_process FILES_TO_PROCESS [FILES_TO_PROCESS ...]]
                                  [--version VERSION] [--language LANGUAGE]

Downloads and processes Mozilla Common Voice dataset 7.0.
```

Arguments Guide
```

optional arguments:                   desc
  -h, --help                          returns help
  
  --data_root DATA_ROOT               Directory to store the dataset.
 
 --manifest_dir MANIFEST_DIR          Output directory for manifests
 
 --num_workers NUM_WORKERS            Workers to process dataset.
 
 --sample_rate SAMPLE_RATE            Sample rate
 
 --files_to_process FILES_TO_PROCESS  list of *.csv file names to process
 
 --version VERSION                  Version of the dataset (obtainable via
                                    https://commonvoice.mozilla.org/en/datasets
 
 --language LANGUAGE                Which language to download.(default english,check
                                    https://commonvoice.mozilla.org/en/datasets for more
                                    language codes.
```
