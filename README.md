# paper_downloader

### Input

DOIs or urls, split by comma.

PMIDs are not supported yet, but URLs from PubMed are acceptable.

### Usage

```shell
~ python ./sci_hub_dl.py 10.1038/s41588-019-0540-6,https://www.nature.com/articles/s41588-019-0540-6

Connected to sci-hub.

The paper you are looking for is:
Gaffney, D. J. (2019). Mapping and predicting gene–enhancer interactions. Nature Genetics. doi:10.1038/s41588-019-0540-6 

Dowload PDF
10.1038@s41588-019-0540-6.pdf: 1.25MB [00:07, 173kB/s]                                         
Saved paper to 10.1038@s41588-019-0540-6.pdf.

Connected to sci-hub.

The paper you are looking for is:
Gaffney, D. J. (2019). Mapping and predicting gene–enhancer interactions. Nature Genetics. doi:10.1038/s41588-019-0540-6 

Dowload PDF
10.1038@s41588-019-0540-6.pdf: 1.25MB [00:23, 56.3kB/s]                                        
Saved paper to 10.1038@s41588-019-0540-6.pdf.
```

### Requirements

- Python3
- requests
- BeautifulSoup
- tqdm