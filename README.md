# CMEMS_NSOAS
## Copernicus Marine Service Toolbox (CLI & Python) Installation
### Mamba | Conda
```bash
mamba install conda-forge::copernicusmarine --yes
```
or Conda
```bash
conda install -c conda-forge copernicusmarine
```
Upgrade using mamba | conda:
```bash
mamba update --name copernicusmarine copernicusmarine --yes
```

### Pip
```bash
python -m pip install copernicusmarine
```
Upgrade using pip:
```bash
python -m pip install copernicusmarine --upgrade
```

## Dataset of Interest
### 1. Global PHY
| Product ID                     | Dataset ID                                               | Variables         | Horizontal And Vertical Resolutions | Temporal Resolution | Temporal Coverage [Start Date; End Date] |
|:------------------------------:|:--------------------------------------------------------:|:-----------------:|:-----------------------------------:|:-------------------:|:----------------------------------------:|
| SEALEVEL_GLO_PHY_L4_MY_008_047 | cmems_obs-sl_glo_phy-ssh_my_allsat-l4-duacs-0.125deg_P1D | SSH U V SLA Ua Va | 1/8° - 1/8°                         | Daily & Monthly     | [1993/1/1; 2023/12/31]                   |
| SEALEVEL_GLO_PHY_L4_NRT_008_046| cmems_obs-sl_glo_phy-ssh_nrt_allsat-l4-duacs-0.125deg_P1D| SSH U V SLA Ua Va | 1/8° - 1/8°                         | Daily               | [2024/11/20; ongoing]                    |
|                                | cmems_obs-sl_glo_phy-ssh_nrt_allsat-l4-duacs-0.25deg_P1D | SSH U V SLA Ua Va | 1/4° - 1/4°                         | Daily               | [2022/1/1; 2024/11/25]                   |
| GLOBAL_MULTIYEAR_PHY_001_030   | cmems_mod_glo_phy_my_0.083deg_P1D-m                      | SSH thetao so uo vo | 1/12° - 1/12° & 50 level          | Daily               | [1993/1/1; 2021/6/30]                    |
|                                | cmems_mod_glo_phy_myint_0.083deg_P1D-m                   | SSH thetao so uo vo | 1/12° - 1/12° & 50 level          | Daily               | [2021/7/1; 2024/12/24]                   |