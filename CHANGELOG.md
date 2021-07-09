# Changelog for version 3.x

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
