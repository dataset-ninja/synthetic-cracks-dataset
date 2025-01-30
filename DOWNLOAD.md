Dataset **Supervisely Synthetic Crack Segmentation** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzE1NDhfU3VwZXJ2aXNlbHkgU3ludGhldGljIENyYWNrIFNlZ21lbnRhdGlvbi9zdXBlcnZpc2VseS1zeW50aGV0aWMtY3JhY2stc2VnbWVudGF0aW9uLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIlE0WE5STi9meWZRclhzSHM5cVVVK29Wb3UzV1Q1S0FEakNUMXVYS3lXODQ9In0=)

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