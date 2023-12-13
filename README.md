# EMNLP-23
Repository for paper "Improving Transformer-based Program Repair Models through False Behavior Diagnosis"  
Here we show example code and data used for the experiment.

[Folders]  
&emsp; A. APR Models  
&emsp;&emsp; - Trained APR models  
&emsp;&emsp; - Trained models can be found in following link:  
&emsp;&emsp;&ensp; https://www.dropbox.com/sh/q94kdtguedgl4f7/AACSMqydlIoQVqVSI91DTTZIa?dl=0  

&emsp; B. Attentions  
&emsp;&emsp; - Sample normalized attention maps used for experiment  
&emsp;&emsp; - Pickle files also contain other infos such as input_id  
&emsp;&emsp; - Entire pickle files for CodeT5 Model with Wild-small^na Dataset can be found in following link:  
&emsp;&emsp;&ensp; https://www.dropbox.com/sh/q94kdtguedgl4f7/AACSMqydlIoQVqVSI91DTTZIa?dl=0  

&emsp; C. Dataset  
&emsp;&emsp; - Buggy dataset (buggy code - fixed code pairs)  

&emsp; D. Extracted Attentions  
&emsp;&emsp; - Temprorary folder to show how we extracted normalized attention map  
&emsp;&emsp; - "1. Collect Normalized Attention.ipynb" shows the extraction process  

[Files]  
&emsp; 1. Collect Normalized Attention.ipynb  
&emsp; 2. Diagnose and T2 Example.ipynb  
&emsp; 3. transformers.zip  
&emsp;&emsp; - We used the modified transformer==4.12.3 for our experiment  
&emsp; 4. README.txt  
&emsp; 5. requriements.txt  
