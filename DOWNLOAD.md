Dataset **IITM-HeTra** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/l/B/SV/jBT65j2o8zYj4edUBXCRbCLdXjNaLuA1Z5fDkFMVuGVdWG11YsAFTadG1l7FCnhN8Ii7RJmCxG5wFmt63tYk8y3focD6tfYHhuGXrztfQpxGB9ghmG8Rb4Zpe1vT.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='IITM-HeTra', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/deepak242424/iitmhetra/download?datasetVersionNumber=2).