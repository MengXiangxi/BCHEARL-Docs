# Demo Data

The demo data are provided to facilitate the understanding of the workflow and providing a template for the task file. It is **HIGHLY** recommended that the user download them and try running the program with them.

## The source of the imaging data

The DICOM files were adapted from [NEMA IQ phantom raw data GE 4-ring DMI](https://zenodo.org/record/6402885) on [Zenodo](https://zenodo.org/) following the [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) license.

> Schramm, Georg, & Baete, Kristof. (2022). NEMA IQ phantom raw data GE 4-ring DMI (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6402885

The DICOM files were taken from the file `raw_data_1e8_prompts.zip`. I took the files in the `raw_1/duetto_workdir/offline3D` folder. Many thanks to my friend Zhan Tong Zhang for preparing the data.

## The structure of the demo data

Upon unzipping, the demo data contain the following files.

```text
D:\BCHEARL_DEMO
│   demoFillData.mat
│   demoROI.mat
│   demoTask.json
│
└───NOT_DIAGNOSTIC_offline3D
        _bin1_sl1.sdcopen
        _bin1_sl10.sdcopen
        _bin1_sl11.sdcopen
        _bin1_sl12.sdcopen
        ...
```

- `demoFillData.mat` is a binary data containing the **filling parameters** of the phantom. The data were fabricated by me. They were not the actual data in the preparation of the phantom.
- `demoROI.mat` is a binary data for the preliminary ROI drawn over the spheres.
- `demoTask.json` is a json task file containing two json instances. It will yield two sets of figure and tables once calculated.
- `NOT_DIAGNOSTIC_offline3D` contains a series of DICOM images. The extension is `.sdcopen`, but the files can be loaded by a DICOM viewer.

## Obtaining the demo data

Download the zip file [here](https://mengxiangxi.info/Link/BCH_EARL.html).

Unzip it to `D:/`, and the new folder will be `D:/BCHEARL_DEMO/`. Of course, you can unzip it anywhere, but you may need to revise the related `"Work Path"` value in the json task file `demoTask.json`.
