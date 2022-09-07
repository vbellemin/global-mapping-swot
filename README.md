# Global Mapping Swot

### Download raw data 

```python
|-- gulf_stream or north_atlantic
|   |-- initial_reconstruction
|   |   |-- all_sats.zarr
|   |   |-- all_sats_filtered.zarr
|   |   |-- nadirs.zarr
|   |   |-- nadirs_filtered.zarr
|   |   |-- swot.zarr
|   |   |-- swot_filtered.zarr
|   |-- noisy_reconstruction
|   |   |-- all_sats.zarr
|   |   |-- all_sats_filtered.zarr
|   |   |-- nadirs.zarr
|   |   |-- nadirs_filtered.zarr
|   |   |-- swot.zarr
|   |   |-- swot_filtered.zarr
|   |-- model 
|   |   |-- glorys12.zarr
|   |   |-- glorys12_filtered.zarr
```

### Download results

```python
|-- osse1-nadirs or osse2-swot or osse3-allsats
|   |-- initial
|   |   |-- error_variance.nc
|   |   |-- error_variance_filtered.nc
|   |   |-- resolution.nc
|   |   |-- ...
|   |-- noisy
|   |   |-- error_variance.nc
|   |   |-- error_variance_filtered.nc
|   |   |-- resolution.nc
|   |   |-- ...
```
