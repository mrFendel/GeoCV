**FIlters**
- [Distance Transform](https://porespy.org/examples/filters/reference/distance_transform_lin.html)
- [Fill blind pores](https://porespy.org/examples/filters/reference/fill_blind_pores.html) - может заполнить вложенные поры
- [Fill Disconnected Voxels](https://porespy.org/examples/filters/reference/find_disconnected_voxels.html) - убирает области не соединенные с краями изображения
- [Trimming Smal Clusters](https://porespy.org/examples/filters/reference/trim_small_clusters.html) - removes isolated voxels or clusters of a given size or smaller.

- [local thickness](https://porespy.org/examples/filters/reference/local_thickness.html) - рисует вписанные окружности и находит их радиусы
- [NL Means Filter](https://porespy.org/examples/filters/reference/nl_means_layered.html) - Applies the non-local means filter to each 2D layer of a 3D image (stack of 2D images) in parallel. This function is applicable in removing noise from SEM images
- [Poroisometry](https://porespy.org/examples/filters/reference/porosimetry.html) - returns a list of invasion sizes which can be analzyed to extract the pore size distribution.
- [Trim Blobs](https://porespy.org/examples/filters/reference/trim_disconnected_blobs.html) - trims disconnected blobs
- [Trim Peaks](https://porespy.org/examples/filters/reference/trim_extrema.html) - flattening peaks

- [Find Peaks](https://porespy.org/examples/filters/reference/find_peaks.html)
- [SNOW Partitioning](https://porespy.org/examples/filters/reference/snow_partitioning.html) + [NPhases](https://porespy.org/examples/filters/reference/snow_partitioning_n.html)
- [ImageJ Plugins](https://porespy.org/modules/generated/generated/porespy.filters.imagej.imagej_wrapper.html) - applying imageJ Filters 3D

**Metrics**
- [pore size distribution](https://porespy.org/examples/metrics/reference/pore_size_distribution.html) - распределение размеров пор
- [Porosity](https://porespy.org/examples/metrics/reference/porosity.html) - пористость
- [Porosity Profile](https://porespy.org/examples/metrics/reference/porosity_profile.html) - пористость вдоль направления
- [Props to DataFrame](https://porespy.org/examples/metrics/reference/props_to_DataFrame.html) - для каждой поры выдает свойства типа сферичности
- [Radial Density DIstribution](https://porespy.org/modules/generated/generated/porespy.metrics.radial_density_distribution.html)
- [Region Interface area](https://porespy.org/examples/metrics/reference/region_interface_areas.html)

**Pretraned Networks**
- [Diffusive Size factor ](https://porespy.org/examples/networks/reference/diffusive_size_factor_AI.html) - predicting the diffusive size factors of the conduit images decribed [here](https://doi.org/10.1016/j.cageo.2022.105086). Note that the diffusive conductance of the conduits can be then calculated by multiplying the size factor by diffusivity of the phase.
- [SNOW2](https://porespy.org/examples/networks/reference/snow2.html)
