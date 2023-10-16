Dataset **Supervisely Synthetic Crack Segmentation** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/D/o/iJ/ponU2obwAkEn7ICvEWlETNT0WEz9u3yAkqQBpAZn9fkAnllfHQTaaiUDkKNFPAoetfkRTBKHSx6FM1vZUGFIT8VYUQPzBac89FaYdAaWZJ7VDD8XalrRukzuCM05.tar)

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