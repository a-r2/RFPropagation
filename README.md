# RFPropagation

The Modelica library RFPropagation includes several of the best-known propagation models used to compute path losses between a radiowave source (radio transmitter) and a radiowave sink (radio receiver) under different scenarios. They address different attributes of the propagation channel: outdoor and indoor, LOS (Line-Of-Sight) and non-LOS, clear path and obstructed path, tropospheric and ionospheric. In addition, the library contains models of physical components such as generic antennas and cables that enables the calculation of link budgets.

<p align="center">
  <img src="https://github.com/a-r2/RFPropagation/blob/main/Example.png?raw=true" width=50% height=50%/>
</p>

## 1. Propagation models:

- Free-space path loss
- Outdoor propagation models
  - Foliage models
    - Weissberger’s model
    - Early ITU vegetation model
  - Terrain models
    - Egli model
    - ITU terrain model
  - Models for built-up areas
    - Young model
    - Okumura model
    - Hata model (with PCS extension)
- Indoor propagation models
  - ITU indoor model
  - The log-distance model

## 2. Package structure:

- Components
  - Antenna
  - Egli
  - FreeSpacePathLoss
  - Hata
  - ITUEarlyVegetation
  - ITUIndoor
  - ITUTerrain
  - LogDistance
  - PartialFreeSpacePathLoss
  - RFCable
  - Okumura
  - WeissbergerFoliage
  - Young
- Examples
  - EgliTest
  - FreeSpacePathLossTest
  - HataTest
  - ITUEarlyVegetationTest
  - ITUIndoorTest
  - ITUTerrainTest
  - LogDistanceTest
  - OkumuraTest
  - WeissbergerFoliageTest
  - YoungTest
- Interfaces
  - AntennaMedium
  - AntennaTerminal
  - PowerFlow
  - RadioTerminal
- Sources
  - PowerSet
- to_dB
- from_dB
- to_dBm
- from_dBm
- Directivity
- PowerdBm
- PowerdB

## 3. References

John S. Seybold. "Introduction to RF Propagation". 9 September 2005. Published by John Wiley & Sons, Inc. DOI: 10.1002/0471743690
