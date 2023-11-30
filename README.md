# EMNLP-23
Repository for paper "Improving Transformer-based Program Repair Models through False Behavior Diagnosis"


Here we show partial code and data used for the experiment.
We are planning to make whole code and data available soon.

[Folders]
  A. APR Models
       - Trained APR models
       - Trained models can be found in following link:
          https://www.dropbox.com/sh/q94kdtguedgl4f7/AACSMqydlIoQVqVSI91DTTZIa?dl=0
  B. Attentions
       - Sample normalized attention maps used for experiment
       - Pickle files also contain other infos such as input_id
       - Entire pickle files for CodeT5 Model with Wild-small^na Dataset can be found in following link:
           https://www.dropbox.com/sh/q94kdtguedgl4f7/AACSMqydlIoQVqVSI91DTTZIa?dl=0
  C. Dataset
       - Buggy dataset (buggy code - fixed code pairs)
  D. Extracted Attentions
      - Temprorary folder to show how we extracted normalized attention map
      - "1. Collect Normalized Attention.ipynb" shows the extraction process

[Files]
  1. Collect Normalized Attention.ipynb
  2. Diagnose and T2 Example.ipynb
  3. transformers.zip
      - We used the modified transformer==4.12.3 for our experiment
  4. README.txt
  5. requriements.txt
