# TMA Faults

| **Requested by:** | **AURA**   |
| ----------------- | ---------- |
| **Doc. Code**     |            |
| **Editor:**       | A. Izpizua |
| **Approved by:**  | J. Garcia  |

## Index

- [TMA Faults](#tma-faults)
  - [Index](#index)
  - [Introduction](#introduction)
  - [Main Axes](#main-axes)
    - [Fault list](#fault-list-1)
    - [Fault tree](#fault-tree)
  - [Encoder system (EIB)](#encoder-system-eib)
    - [Fault list](#fault-list-2)
    - [Fault tree](#fault-tree-1)

## Introduction

bla, bla

## Main Axes

The list is for main axes, elevation and azimuth. If two number appears in the fault code, the one for azimuth axis is 1xx while for the elevation axis is 4xx.

### Fault list

|Code|Name|Type|Description|Possible Solution|
|--|--|--|--|--|

### Fault tree

## Encoder system (EIB)

### Fault list

|Code|Name|Type|Description|Possible Solution|
|--|--|--|--|--|
|710|Timeout|Fault|Depends on the command in execution|Depends on the command faulted|
|755|Reference mark error|Warning|Reference mark calculation error for heads: failed head names.Possible a reference mark is missing|Check the tape and clean if necessary|
|756|Not all heads have a valid reference|Warning|When calculating the head reference value, the heads failed head names failed. They will not be used for absolute position calculation|Try homing again. Some positions are badly calculated for azimuth, the calculated position is 360 deg away from the actual position, and can't not be used|

### Fault tree