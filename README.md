# Charlotte SAC nfl_data_py Intro
Unfortunately, installing this package sucks. It works as intended on Python versions 3.10-3.12, but  we are going to try to get around installing older Python versions by using this line to install nfl_data_py. <br>
```Python
pip install numpy>=2.0 pandas fastparquet appdirs && pip install nfl_data_py --no-deps
```

If you run that and no errors pop up, run this line in a new cell and see if a table appears.
```Python
import nfl_data_py as nfl
nfl.import_pbp_data(years = [2025])
```
