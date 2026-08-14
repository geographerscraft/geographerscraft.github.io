# Coordinate Systems Overview

**Author:** Peter H. Dana  
**Affiliation:** Department of Geography, University of Texas at Austin  
**Source:** The Geographer's Craft Project

---

## Overview

This page serves as a comprehensive primer on the mathematical and physical foundations of geographic coordinates. It explains the necessity of coordinate systems for mapping and positioning, covering both local and global systems.

---

## Major Sections & Topics Covered

### 1. Introduction

- Necessity of coordinate systems for mapping and positioning

### 2. Basic Coordinate Systems

**2-D Cartesian (Planar):**

- For small area maps
- X, Y coordinates

**Spherical:**

- Latitude and Longitude for global representation
- Angular measurements

**3-D Cartesian (Geocentric):**

- Earth-centered systems (X, Y, Z)
- Used in satellite positioning

### 3. Reference Ellipsoids

Discusses Earth's shape and key ellipsoids:

- **Clarke 1866** - Used for NAD27
- **GRS80** (Geodetic Reference System 1980) - Used for NAD83
- **WGS84** (World Geodetic System 1984) - Used by GPS

### 4. Geodetic Datums

Explains how ellipsoids are aligned to the Earth's surface:

- Horizontal datums
- Vertical datums

---

## Key Coordinate Systems & Datums

### Geodetic Datums

| Datum     | Ellipsoid   | Usage                                           |
| --------- | ----------- | ----------------------------------------------- |
| **NAD27** | Clarke 1866 | North American Datum 1927 (historical)          |
| **NAD83** | GRS80       | North American Datum 1983 (current US standard) |
| **WGS84** | WGS84       | World Geodetic System 1984 (GPS standard)       |

### Global Systems

- **Latitude and Longitude:** Angular measurements for global positioning (degrees, minutes, seconds or decimal degrees)

### Grid Systems

| System     | Description                                                     |
| ---------- | --------------------------------------------------------------- |
| **UTM**    | Universal Transverse Mercator - Global grid, 60 zones           |
| **MGRS**   | Military Grid Reference System - Alphanumeric, based on UTM/UPS |
| **UPS**    | Universal Polar Stereographic - Polar regions                   |
| **SPCS**   | State Plane Coordinate System - US high-accuracy local mapping  |
| **BNG**    | British National Grid - UK Ordnance Survey                      |
| **ING**    | Irish National Grid - Ireland mapping                           |
| **GEOREF** | World Geographic Reference System - Aircraft position reporting |

---

## UTM Zone Details

- 60 zones worldwide (6° wide each)
- Zones numbered 1-60, west to east
- Northern and Southern hemispheres
- False easting: 500,000 meters
- False northing: 0 (N) or 10,000,000 (S)

---

## State Plane Coordinate System (SPCS)

- Used in United States
- Designed for high-accuracy local mapping
- Originally based on NAD27
- Updated for NAD83
- Uses either:
  - Lambert Conformal Conic (E-W extent states)
  - Transverse Mercator (N-S extent states)

---

## Archive Information

**Original URL:** `http://www.colorado.edu/geography/gcraft/notes/coordsys/coordsys_f.html`  
**Archive URL:** `https://web.archive.org/web/20020806045349/http://www.colorado.edu/geography/gcraft/notes/coordsys/coordsys_f.html`

---

## Modernization Notes for Version 2

This content should be updated to include:

- **ITRF** (International Terrestrial Reference Frame) - modern geodetic reference
- **NAD83(2011)** - latest NAD83 realization
- **EPSG Codes** - standard identifiers for each system
- **PROJ library** integration
- **Web Mercator (EPSG:3857)** - web mapping standard
- **GeoJSON** and modern data formats
- **Time-dependent coordinates** (plate tectonics)
- **Online coordinate transformation tools**

---

## Related Modules

- GPS Overview (Dana)
- Map Projections (Dana)
- Geodetic Datums

---

_Archived: 2026-01-18_
