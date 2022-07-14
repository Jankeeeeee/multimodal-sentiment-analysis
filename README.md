# multimodal-sentiment-analysis
人工智能课程实验五：多模态情感分析
  
## Setup
This implemetation is based on Python3. To run the code, you need the following dependencies:

- chardet==3.0.4
- Pillow==7.1.2
- pandas==1.3.5
- nltk==3.7
- torch==1.12.0
- torchvision==0.13.0

You can simply run

```shell
pip install -r requirements.txt
```

## Repository structure

```shellsession
│  process_data.ipynb    # Process datas into json
│  model.ipynb    # text and vision model
│  README.md
│  requirements.txt
│  train.txt
|  train.json
|  val.json
|  test.json
|
└─data # the folder that contains data examples
```

## Run
+ process_data.ipynb(Optional)

处理后的json文件已经在仓库中给出，故该代码执行可选

+ model.ipynb

在colab中按步骤顺序执行即可


