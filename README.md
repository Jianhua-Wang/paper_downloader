# paper_downloader

### Input

Dois or urls split by comma (PMID not support yet).

### Usage

```shell
~ python sci_hub_dl.py 10.1038/s41588-019-0540-6,10.1186/s13059-019-1855-4

Connected to sci-hub.

The paper you are looking for is:
Gaffney, D. J. (2019). Mapping and predicting gene–enhancer interactions. Nature Genetics. doi:10.1038/s41588-019-0540-6 

Dowload PDF
10.1038@s41588-019-0540-6.pdf: 1.25MB [00:30, 42.8kB/s]                                        
Saved paper to 10.1038@s41588-019-0540-6.pdf.

Connected to sci-hub.

The paper you are looking for is:
Gorkin, D. U., Qiu, Y., Hu, M., Fletez-Brant, K., Liu, T., Schmitt, A. D., … Ren, B. (2019). Common DNA sequence variation influences 3-dimensional conformation of the human genome. Genome Biology, 20(1). doi:10.1186/s13059-019-1855-4 

Dowload PDF
10.1186@s13059-019-1855-4.pdf: 3.41MB [01:03, 56.1kB/s]                                        
Saved paper to 10.1186@s13059-019-1855-4.pdf.
```

### Requirements

- Python3
- requests
- BeautifulSoup
- tqdm