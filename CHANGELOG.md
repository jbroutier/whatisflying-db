# Changelog for version 3.x

## Version 3.3.0

**New data**

- aircraft: Add 353 Aérospatiale aircraft.
- aircraft: Add 4 Airbus aircraft.
- aircraft: Add 343 Airbus Helicopter aircraft.
- aircraft: Add 183 MBB/Kawasaki aircraft.
- aircraft types: Add 6 aircraft types.
- aircraft types: Add 6 aircraft types pictures.

**Removed data**

- aircraft: Remove 23 outdated Airbus Helicopters aircraft.

**Fixes & improvements**

- aircraft: Fix a lot of Airbus Helicopters aircraft data (model names, types, …).
- aircraft: Move Airbus Helicopters aircraft to separate file.
- aircraft: Sort MBB aircraft.
- aircraft types: Fix aircraft type `EC20` name.

## Version 3.2.0

**New data**

- aircraft: Add 1 Boeing aircraft.
- aircraft: Add 956 Mil aircraft.
- aircraft: Add 2083 Robin aircraft.
- aircraft: Add 7411 Robinson aircraft.
- aircraft: Add 265 aircraft pictures.
- aircraft types: Add 23 aircraft types.
- aircraft types: Add 27 aircraft types pictures.

**Fixes & improvements**

- aircraft: Fix aircraft `ac82ec` type code.
- aircraft types: Fix aircraft type `AC56` picture.

## Version 3.1.0

**New data**

- aircraft: Add 35 Focke-Wulf aircraft.
- aircraft: Add 312 Fokker aircraft.
- aircraft types: Add 15 aircraft types.
- aircraft types: Add 13 aircraft types pictures.

## Version 3.0.0

**New data**

- aircraft: Add 31 Airbus aircraft.
- aircraft: Add 11 ATR aircraft.
- aircraft: Add 61 Boeing aircraft.
- aircraft: Add 32 Embraer aircraft.
- aircraft: Add 469 Pilatus aircraft.
- aircraft types: Add new columns: `climb_rate`, `never_exceed_speed`, `ferry_range`, `oew` and `auw`.
- navaids: Add ILS outer markers (660+), middle markers (450+) and inner markers (150+).

**Fixes & improvements**

- aircraft types: Remove description and wake turbulence category for generic types.
- aircraft types: Rework technical data.
- navaids: Update data (decommissioned NDBs were removed).
- navaids: Improve names formatting (no more truncated/capital letters names).
- navaids: Round the `latitude` and `longitude` columns to 5 decimal places.
- navaids: Set the type of DMEs associated with NDBs to `DME-NDB`. These navaids were previously undifferentiated from terminal, standalone NDBs.
- navaids: Split data across multiple files, each one containing only a single navaid type.
