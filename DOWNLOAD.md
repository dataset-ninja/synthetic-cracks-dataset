Dataset **Supervisely Synthetic Crack Segmentation** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/t/z/jx/F8ebZ7VWhhkBzbNE9ITrerYjGX7WZxdS6b3KYspxCc06CCmzmTXPbuf43IE7FN89HjBMlEsAM9s761usZmqiq1aOQXOdXn6pWGG8d1SYzjMsDTyUZDXg8W8NCuEP.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Supervisely Synthetic Crack Segmentation', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://supervisely.com/blog/introducing-supervisely-synthetic-crack-segmentation-dataset/).