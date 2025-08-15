Dataset **Supervisely Synthetic Crack Segmentation** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTU0OF9TdXBlcnZpc2VseSBTeW50aGV0aWMgQ3JhY2sgU2VnbWVudGF0aW9uL3N1cGVydmlzZWx5LXN5bnRoZXRpYy1jcmFjay1zZWdtZW50YXRpb24tRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAibGdDVVBwWGoxd3pta3lXV2RDV2hoZUNhek1QSlhKdENUUDdpUTA3Z1NFUT0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22supervisely-synthetic-crack-segmentation-DatasetNinja.tar%22)

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