# HiOverlay
Interactive and Online Overlay Analytics of Large Spatial Data. An online demo is provided on the Web( [DEMO](http://www.higis.org.cn:8080/hioverlay/)). The datasets and hardware environment of the DEMO is shown as follows. Experiments  on an SMP server(32 cores/64 threads) verify that our approach is capable of handling ten-million-scale data.



***Tab1. Datasets of Spain from [OpenStreetMap](https://download.geofabrik.de/europe/spain-latest.osm.pbf)*** ([Classification standard](https://wiki.openstreetmap.org/wiki/Map_Features))

| Name                                  | Type       | Records   | Size                |
| ------------------------------------- | ---------- | --------- | ------------------- |
| Amenity_Education                     | Point      | 6,994     | 6,994 Points        |
| Amenity_Entertainment, Arts & Culture | Point      | 6,928     | 6,928 Points        |
| Amenity_Financial                     | Point      | 13,040    | 13,040 Points       |
| Amenity_Healthcare                    | Point      | 14,757    | 14,757 Points       |
| Amenity_Sustenance                    | Point      | 8,9282    | 89,282 Points       |
| Amenity_Transportation                | Point      | 3,114     | 3,114 Points        |
| Shop                                  | Point      | 82,192    | 82,192 Points       |
| Religion                              | Point      | 6,219     | 6,219 Points        |
| Historic                              | Point      | 14,974    | 14,974 Points       |
| Leisure                               | Point      | 8,334     | 8,334 Points        |
| Tourism                               | Point      | 36,462    | 36,462 Points       |
| Places                                | Point      | 582,464   | 582,464 Points      |
| Public_Transport                      | Point      | 45,478    | 45,478 Points       |
| Railway                               | Linestring | 97,675    | 309,716 segments    |
| Highway                               | Linestring | 3,132,496 | 42,497,196 segments |
| Waterway                              | Linestring | 33,214    | 4,254,732 segments  |
| Natural_Beach                         | Point      | 148       | 148 Points          |
| Natural_Cave                          | Point      | 3,237     | 3,237 Points        |
| Natural_Cliff                         | Point      | 155       | 155 Points          |
| Natural_Peak                          | Point      | 28,106    | 28,106 Points       |
| Natural_Spring                        | Point      | 4,780     | 4,780 Points        |
| Natural_Tree                          | Point      | 533,856   | 533,856 Points      |
| Natural_Volcano                       | Point      | 13        | 13 Points           |

***Tab2.  Demo Environment***

| Item             | Description                                      |
| ---------------- | ------------------------------------------------ |
| CPU              | 4core*2, Intel(R) Xeon(R) CPU E5-2680 v3@2.50GHz |
| Memory           | 32 GB                                            |
| Operating System | Centos7                                          |

