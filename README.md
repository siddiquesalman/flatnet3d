# FlatNet3D
Official test code for *FlatNet3D: intensity and absolute depth from single-shot lensless capture,* Optica JOSA A (2022)[[Link]](https://opg.optica.org/josaa/abstract.cfm?uri=josaa-39-10-1903).

Use the ```flatnet3d_test.ipynb``` for testing. Before using it, please note the following instructions:
1. Checkpoints are available at this [link](https://www.dropbox.com/s/6f73g58iem9iip3/model_2dunet_50dB_reg_48.pt?dl=0). Download the ```.pt``` file and save it in the ```checkpoint``` directory of this repo.
2. Test data is available at this [link](https://www.dropbox.com/sh/3u2oe8gscj38hx8/AADIUhmPK0qTmsOHqnwX_jrRa?dl=0). Download the test files to ```data``` directory of this repo. Make sure you download the PSF stack named ```psfs_save_magfs.mat``` to this directory too. 

If you use this code in your work, please include the following reference:
```
@article{bagadthey2022flatnet3d,
  title={FlatNet3D: intensity and absolute depth from single-shot lensless capture},
  author={Bagadthey, Dhruvjyoti and Prabhu, Sanjana and Khan, Salman S and Fredrick, D Tony and Boominathan, Vivek and Veeraraghavan, Ashok and Mitra, Kaushik},
  journal={JOSA A},
  volume={39},
  number={10},
  pages={1903--1912},
  year={2022},
  publisher={Optica Publishing Group}
}
```
