# satfilename
python module &amp; CLI utility for generating standard satellite product filenames

# installation
```
git clone https://github.com/USF-IMaRS/satfilename
cd satfilename
pip3 install -e .
```

# usage
## python module
```python
import satfilename

path_to_a_modis_aqua_file = satfilename.myd01(
    datetime(2000, 1, 2, 3, 45),
    "my-region-name"
)
```

## CLI
** under development **

```
you@your_comp:~$ echo satfilename -t 2000-01-02T3:45 -r 'my-region-name' l1a_lac_hdf_bz2
/srv/imars-objects/modis_aqua_my-region-name/l1a_lac_hdf_bz2/A2000002034500.L1A_LAC.x.hdf.bz2
```
