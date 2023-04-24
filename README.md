# mom6-isomip-svtest

Repository of MOM6 ISOMIP test configurations in different coordinates.

`analysis` contains some analysis notebooks

`common-layer` contains the `MOM_input`, `input.nml` and `diag_table` from the [MOM6-examples ISOMIP layer example](https://github.com/NOAA-GFDL/MOM6-examples/tree/dev/gfdl/ocean_only/ISOMIP/layer)

Each folder is a different experiment, which uses the same `MOM_input` plus a unique `MOM_override`

The folders in this main branch are different vertical coordinates, and testing the use of KV_ML_INVZ2. The branch `Testing` has lots more experiments, with different stratification and some playing around with the number of vertical levels.

 
