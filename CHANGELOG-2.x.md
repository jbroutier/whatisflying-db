# Changelog for version 2.x

**Version 2.0.19**

- Add 5 English Electric aircraft.
- Add 26 Fieseler aircraft.
- Add 34 Messerschmitt aircraft.
- Add 78 Mikoyan-Gurevich aircraft.
- Add 52 Morane-Saulnier aircraft.
- Add 217 aircraft pictures.
- Add 19 aircraft types.
- Add 19 aircraft types pictures.

**Version 2.0.18**

- Add 77 AgustaWestland aircraft.
- Add 140 Avro aircraft.
- Add 66 BAC aircraft.
- Add 18 Bell/Boeing aircraft?
- Add 183 British Aerospace aircraft.
- Add 22 aircraft types.
- Add 22 aircraft types pictures.

**Version 2.0.17**

- Add 37 Aermacchi aircraft.
- Add 421 Aero Vodochody aircraft.
- Add 711 Cirrus aircraft.
- Add 466 aircraft pictures.
- Add 14 aircraft types.
- Add 12 aircraft types pictures.
- Fix aircraft `ad120c` model.

**Version 2.0.16**

- Add 274 Boeing aircraft.
- Add 107 British Aerospace aircraft.
- Add 999 Lockheed aircraft.
- Add 712 McDonnell Douglas aircraft.
- Add 67 aircraft pictures.
- Add 18 aircraft types pictures.
- Fix aircraft type C17 manufacturer name.
- Fix aircraft type G96 name.
- Fix aircraft type HAWK manufacturer name & name.
- Fix aircraft type T33 name.

**Version 2.0.15**

- Remove 5 duplicate Airbus aircraft.

**Version 2.0.14**

- Add 65 Airbus aircraft.
- Add 3 Cessna aircraft.
- Add 6959 Piper aircraft.
- Add 230 aircraft pictures.
- Fix 18 Piper aircraft types names.
- Replace aircraft type C30J picture (better quality).

**Version 2.0.13**

- Add 42 Airbus aircraft.
- Add 2 ATR aircraft.
- Add 16 Boeing aircraft.
- Add 6 Embraer aircraft.
- Add AirAsia India (IAD/I5) airline.

**Version 2.0.12**

- Add 20 Schweizer aircraft.
- Add 1456 Sikorsky aircraft.
- Add 192 aircraft pictures.
- Update aircraft type S330 manufacturer name.

**Version 2.0.11**

- Add 6446 Bell aircraft.
- Add 536 Mooney aircraft.

**Version 2.0.10**

- Add 594 Dassault aircraft.
- Add 365 Lockheed Martin aircraft.
- Add 189 aircraft pictures.
- Remove wrong Cessna E350 aircraft type picture.

**Version 2.0.9**

- Add 3 Airbus aircraft.
- Add 1 Boeing aircraft.
- Add 1201 MD Helicopters aircraft.
- Add 1118 Morane Saulnier aircraft.
- Add 155 Northrop aircraft.
- Add the surface type of 8515 airport runways.

**Version 2.0.8**

- Add 307 Grumman American aircraft.
- Add 18 Gulfstream American aircraft.
- Add 58 Hawker Siddeley aircraft.
- Add 251 MBB aircraft.
- Add 1039 aircraft pictures.
- Add aircraft type E530 picture.

**Version 2.0.7**

- Add 22 ERCO aircraft.
- Add 202 Eurofighter aircraft.
- Add 1040 Hughes aircraft.
- Add 1 Aero Vodochody aircraft.
- Add 303 Jodel aircraft.
- Add 102 aircraft pictures.
- Add 2 Sikorsky aircraft types pictures.
- Add 1 Aero Vodochody aircraft type picture.
- Fix aircraft type A270 manufacturer name.
- Fix aircraft type D11 name.
- Fix aircraft type H269 manufacturer name.

**Version 2.0.6**

- Add 8146 Cessna aircraft.
- Add 180 aircraft pictures.

**Version 2.0.5**

- Add 958 Cessna aircraft.
- Add 1 navaid.
- Add 3058 airport statistic datasets for year 2020.
- Fix 3 Cessna aircraft types names.
- Fix navaids incorrectly marked as DME-ILS instead of terminal, non-paired DMEs.

**Version 2.0.4**

- Fix broken CSV.

**Version 2.0.3**

- Add 6141 Cessna aircraft.
- Add 197 Czech Sport Aircraft aircraft.
- Fix aircraft type CRUZ manufacturer name.
- Fix aircraft type T50 name.

**Version 2.0.2**

- Add 6174 Beechcraft aircraft.
- Add 4 Nextant Aerospace aircraft.
- Add Nextant Aerospace 400XT (BE4W) aircraft type.
- Fix 5 Beechcraft aircraft types names.

**Version 2.0.1**

- Add 40 Airbus aircraft.
- Add 3 ATR aircraft.
- Add 205 Boeing aircraft.
- Add 32 Bombardier aircraft.
- Add 500 Embraer aircraft.
- Add 209 Fairchild aircraft.
- Add 237 General Dynamics aircraft.
- Add 433 Grumman American aircraft.
- Add 338 aircraft pictures.
- Add 8 airlines.
- Replace the old Berlin-Schönefeld (EDDB/SXF) airport with the new Berlin-Brandenburg (EDDB/BER) airport.
- Fix the aircraft type E50P name.

**Version 2.0.0**

- Fix ICAO aircraft type code for AgustaWestland AW119 family aircraft.
- Add missing ICAO aircraft type code for aircraft ad5f08.
- Add *slug* column to `navaids.csv` file.
- Add `fixes.csv` file with 220,347 fixes/waypoints.
- Don't quote values unless necessary.

**BC breaking changes:**

- Convert all pictures to WebP format.
- Use empty columns instead of `NULL` keywords to represent null values.
- Use semicolons as multiple values (array) separators.
- Add `airline_logos.csv` to reference airlines logos.
- Rename multiple files to keep a logical sort order.
- Delete unused `airport_pictures.csv` file.
- Rename *airline* column to *operator* to reflect real column usage in `aircraft.csv` and `aircraft/*.csv` files
- Rename *maximum_fuel_capacity* column to *fuel_capacity* in `aircraft_type.csv`.
- Rename *maximum_landing_weight* column to *mlw* in `aircraft_type.csv`.
- Rename *maximum_ramp_weight* column to *mrw* in `aircraft_type.csv`.
- Rename *maximum_takeoff_weight* column to *mtow* in `aircraft_type.csv`.
- Rename *maximum_zero_fuel_weight* column to *mzfw* in `aircraft_type.csv`.
- Rename *range* column to *operating_range* in `aircraft_type.csv`.
- Rename *fleet_age* column to *average_fleet_age* in `airlines.csv`.
- Rename *loc_heading* column to *localizer_heading* in `navaids.csv`.
- Rename *gs_angle* column to *glide_slope_angle* in `navaids.csv`.
- Delete unused *aircraft* column in `airlines.csv`.
- Delete unused *aircraft_models* column in `airlines.csv`.
- Delete unused *connections* column in `airlines.csv`.
- Delete unused *routes* column in `airlines.csv`.
- Delete unused *proc_runways* column in `airports.csv`.
