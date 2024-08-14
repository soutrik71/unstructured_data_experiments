# unstructured_data_experiments

## __LayoutParser__ - A simple and efficient framework for end-to-end document layout analysis
conda create -n detectron2 python=3.10
pip install -r requirements.txt --no-cache-dir
!sudo apt-get install poppler-utils #pdf2image dependency -- restart runtime/kernel after installation
!sudo apt-get install tesseract-ocr-eng #install Tesseract OCR Engine --restart runtime/kernel after installation
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=10.2 -c pytorch
python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
pip install layoutparser
pip install "layoutparser[ocr]"
### Get model weights and config
https://stackoverflow.com/questions/65327162/detectron2-checkpoint-not-found
https://github.com/Layout-Parser/layout-parser/blob/main/src/layoutparser/models/detectron2/catalog.py
https://github.com/Layout-Parser/layout-parser/issues/168
### pdf to image for large pdfs
https://stackoverflow.com/questions/66636441/pdf2image-library-failing-to-read-pdf-signed-using-docusign/74313286#74313286

##__GPT4O___

https://oai.azure.com/portal/0f7c567d04134a9fa9b99f6d834e12b0/chat?tenantid=cef04b19-7776-4a94-b89b-375c77a8f936

| Group   | Atividade                              | SLA              |  
|---------|-----------------------------------------|------------------|  
| **Group 1** |                                       |                  |  
| CORE    | Project / Process Management            | From 5 to 10 days|  
|         | Application development / integrations  |                  |  
| **Group 2** |                                       |                  |  
| TREND   | data scientist                           | From 5 to 20 days|  
|         | PowerBI DAX/M developer                  |                  |  
|         | Data engineer                            |                  |  
|         | Cloud Solutions Architect                |                  |  
|         | Elastic Search Developer                 |                  |  
| **Group 3** |                                       |                  |  
| SCARCE  | Outsystems developer                     | From 5 to 25 days|  
|         | Perl Developer, Python                   |                  |  
|         | OTRS Consultant (Perl)                   |                  |  
