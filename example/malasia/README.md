## Test SHAFTS 

Here we test SHAFTS using the pretrained model on new input satellite iamges in Malaysa.

### Local installation of SHAFTS

To install shafts package locally using this fork version:

1. Download and install `anaconda`, or [`miniconda`](https://docs.conda.io/projects/miniconda/en/latest/)
2. Createand activate a python virtual enviroment with python 3.9:

    `conda create --name shafts_local python=3.9`
    
    `conda activate shafts_local`
3. Install `gdal` using conda:
    `conda install gdal libgdal`
4. Install the following dependencies using `pip`:
    `pip install pandas markupsafe==2.0.1 werkzeug==0.15 pytz`
5. Install `shafts`locally:
    `pip install -e your-repo/src`
    


### Downloading satellite data manually


