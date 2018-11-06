# Twitter API data extraction

This repository demonstrates the application of the Twython library (https://twython.readthedocs.io/en/latest/) for obtaining information from the Twitter API service. The `Tweet_extraction` jupyter notebook contains production-ready code for getting periodic batches of tweets while ensuring no repetitions occur in retrieval. Read the twitter API documentation carefully to understand the OAuth procedure before using.

## Prerequisites

Repository uses Jupyter to host the python code, thus the `.ipynb` extension. Can be used as a regular python script too.

### Software version:
    - Python 3
    - Jupyter notebook 5.0.0

### Python packages:
    - twython
    - json
    - pandas
    - csv
    - re (regular expressions)
    - importlib

To install python packages:
```
$ pip install __PackageName__
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* doLoop Technologies, Mumbai, India for the opportunity to work on this as a side project.
