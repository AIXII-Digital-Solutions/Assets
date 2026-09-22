# Aircraft Templates

Blank (all-white) side-view aircraft templates for livery mock-ups and for displaying aircraft types on the AIXII portal.

Every aircraft type comes in two views:

| View | Description |
|------|-------------|
| **Airborne** | aircraft in flight, landing gear retracted |
| **On the ground** | same aircraft with landing gear extended |

All images are PNG with a transparent background, cropped tightly to the aircraft outline (no padding), about 900–1000 px wide.

## Repository layout

```
Airborne/
├── Passenger/   187 templates
└── Cargo/       72 templates
On the ground/
├── Passenger/   187 templates
└── Cargo/       72 templates
```

The folder structure and file names are identical in `Airborne` and `On the ground`, so a template for one view can be turned into the other just by swapping the top-level folder.

## Naming

File names follow the `aircraft_type` column of the AIXII aircraft types table: `<Manufacturer> <Model> <Category>.png`, where the category is `Passenger` or `Cargo`.

```
Airbus A320 Passenger.png
Airbus A300-600 Cargo.png
```

Some types also have alternative versions (engine options, winglets, freighter conversions). These keep the base name and add the variant in brackets:

```
Airbus A320 Passenger (V2500, sharklets).png
Boeing 757-200 Cargo (PF-PCF, RR).png
```

The file without brackets is the default template for that type.

Only `/` is not allowed in file names, so it is replaced with `-` (for example `Boeing 777-8/9` becomes `Boeing 777-8-9 Passenger.png`).

## Direct image links

The repository is public, so every template can be used as a direct image URL without authentication:

```
https://raw.githubusercontent.com/AIXII-Digital-Solutions/Assets/Aircrafts-Templates/<view>/<category>/<file name>
```

Spaces and other special characters must be URL-encoded, for example:

```
https://raw.githubusercontent.com/AIXII-Digital-Solutions/Assets/Aircrafts-Templates/Airborne/Passenger/Airbus%20A320%20Passenger.png
https://raw.githubusercontent.com/AIXII-Digital-Solutions/Assets/Aircrafts-Templates/On%20the%20ground/Cargo/Boeing%20777-200%20Cargo.png
```

These URLs return the PNG itself (`Content-Type: image/png`), so they can be used directly in an `<img>` tag or stored in a database.

## Notes on coverage

- Templates exist only for types with a suitable side-view illustration. Helicopters, eVTOL, most business jets and many regional types are not covered yet.
- Closely related variants that look the same from the side use the same illustration (for example MD-81/82/83/88, CRJ100/CRJ200, Tu-204/Tu-214, ATR 72-500/-600, and the same airframe listed under different manufacturers).
- If a type is listed as `Cargo` but no dedicated freighter illustration exists, the `Cargo` file is a copy of the passenger template. Freighter conversions look almost identical from the side, apart from the covered windows.
- Boeing 747-200, 747-300 and Saab 340A are listed as `Cargo` only, so their templates are stored under `Cargo` even though the illustrations show the passenger version.

## Source and credits

The base illustrations are the free blank templates by **Norebbo** ([norebbo.com](https://www.norebbo.com/category/aircraft-templates/)). For this repository they were converted to transparent PNGs, split into airborne and on-the-ground views, cropped and renamed to match the AIXII aircraft type list. Full-resolution vector and PSD source files are available at [shopnorebbo.com](https://www.shopnorebbo.com/). All rights to the original illustrations belong to their author.

## Index

<details>
<summary>Passenger (187)</summary>

| Aircraft type | Airborne | On the ground |
|---|---|---|
| ATR ATR 42 300 Passenger | [png](Airborne/Passenger/ATR%20ATR%2042%20300%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2042%20300%20Passenger.png) |
| ATR ATR 42 400 Passenger | [png](Airborne/Passenger/ATR%20ATR%2042%20400%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2042%20400%20Passenger.png) |
| ATR ATR 42 500 Passenger | [png](Airborne/Passenger/ATR%20ATR%2042%20500%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2042%20500%20Passenger.png) |
| ATR ATR 42 600 Passenger | [png](Airborne/Passenger/ATR%20ATR%2042%20600%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2042%20600%20Passenger.png) |
| ATR ATR 72 200 Passenger | [png](Airborne/Passenger/ATR%20ATR%2072%20200%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2072%20200%20Passenger.png) |
| ATR ATR 72 500 Passenger | [png](Airborne/Passenger/ATR%20ATR%2072%20500%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2072%20500%20Passenger.png) |
| ATR ATR 72 600 Passenger | [png](Airborne/Passenger/ATR%20ATR%2072%20600%20Passenger.png) | [png](On%20the%20ground/Passenger/ATR%20ATR%2072%20600%20Passenger.png) |
| Airbus A220 Passenger | [png](Airborne/Passenger/Airbus%20A220%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A220%20Passenger.png) |
| Airbus A220-100 Passenger | [png](Airborne/Passenger/Airbus%20A220-100%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A220-100%20Passenger.png) |
| Airbus A220-300 Passenger | [png](Airborne/Passenger/Airbus%20A220-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A220-300%20Passenger.png) |
| Airbus A300-600 Passenger | [png](Airborne/Passenger/Airbus%20A300-600%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A300-600%20Passenger.png) |
| Airbus A310 Passenger | [png](Airborne/Passenger/Airbus%20A310%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A310%20Passenger.png) |
| Airbus A318 Passenger (PW) | [png](Airborne/Passenger/Airbus%20A318%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A318%20Passenger%20%28PW%29.png) |
| Airbus A318 Passenger | [png](Airborne/Passenger/Airbus%20A318%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A318%20Passenger.png) |
| Airbus A319 Passenger (CFM56, sharklets) | [png](Airborne/Passenger/Airbus%20A319%20Passenger%20%28CFM56%2C%20sharklets%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A319%20Passenger%20%28CFM56%2C%20sharklets%29.png) |
| Airbus A319 Passenger (V2500) | [png](Airborne/Passenger/Airbus%20A319%20Passenger%20%28V2500%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A319%20Passenger%20%28V2500%29.png) |
| Airbus A319 Passenger (V2500, sharklets) | [png](Airborne/Passenger/Airbus%20A319%20Passenger%20%28V2500%2C%20sharklets%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A319%20Passenger%20%28V2500%2C%20sharklets%29.png) |
| Airbus A319 Passenger | [png](Airborne/Passenger/Airbus%20A319%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A319%20Passenger.png) |
| Airbus A319neo Passenger (PW) | [png](Airborne/Passenger/Airbus%20A319neo%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A319neo%20Passenger%20%28PW%29.png) |
| Airbus A319neo Passenger | [png](Airborne/Passenger/Airbus%20A319neo%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A319neo%20Passenger.png) |
| Airbus A320 Passenger (CFM56, sharklets) | [png](Airborne/Passenger/Airbus%20A320%20Passenger%20%28CFM56%2C%20sharklets%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A320%20Passenger%20%28CFM56%2C%20sharklets%29.png) |
| Airbus A320 Passenger (V2500) | [png](Airborne/Passenger/Airbus%20A320%20Passenger%20%28V2500%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A320%20Passenger%20%28V2500%29.png) |
| Airbus A320 Passenger (V2500, sharklets) | [png](Airborne/Passenger/Airbus%20A320%20Passenger%20%28V2500%2C%20sharklets%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A320%20Passenger%20%28V2500%2C%20sharklets%29.png) |
| Airbus A320 Passenger | [png](Airborne/Passenger/Airbus%20A320%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A320%20Passenger.png) |
| Airbus A320neo Passenger (PW) | [png](Airborne/Passenger/Airbus%20A320neo%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A320neo%20Passenger%20%28PW%29.png) |
| Airbus A320neo Passenger | [png](Airborne/Passenger/Airbus%20A320neo%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A320neo%20Passenger.png) |
| Airbus A321 Passenger (CFM56, sharklets) | [png](Airborne/Passenger/Airbus%20A321%20Passenger%20%28CFM56%2C%20sharklets%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A321%20Passenger%20%28CFM56%2C%20sharklets%29.png) |
| Airbus A321 Passenger (V2500) | [png](Airborne/Passenger/Airbus%20A321%20Passenger%20%28V2500%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A321%20Passenger%20%28V2500%29.png) |
| Airbus A321 Passenger (V2500, sharklets) | [png](Airborne/Passenger/Airbus%20A321%20Passenger%20%28V2500%2C%20sharklets%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A321%20Passenger%20%28V2500%2C%20sharklets%29.png) |
| Airbus A321 Passenger | [png](Airborne/Passenger/Airbus%20A321%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A321%20Passenger.png) |
| Airbus A321neo Passenger (LR) | [png](Airborne/Passenger/Airbus%20A321neo%20Passenger%20%28LR%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A321neo%20Passenger%20%28LR%29.png) |
| Airbus A321neo Passenger (PW) | [png](Airborne/Passenger/Airbus%20A321neo%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A321neo%20Passenger%20%28PW%29.png) |
| Airbus A321neo Passenger | [png](Airborne/Passenger/Airbus%20A321neo%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A321neo%20Passenger.png) |
| Airbus A330 Passenger | [png](Airborne/Passenger/Airbus%20A330%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A330%20Passenger.png) |
| Airbus A330-200 Passenger (GE) | [png](Airborne/Passenger/Airbus%20A330-200%20Passenger%20%28GE%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-200%20Passenger%20%28GE%29.png) |
| Airbus A330-200 Passenger (PW) | [png](Airborne/Passenger/Airbus%20A330-200%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-200%20Passenger%20%28PW%29.png) |
| Airbus A330-200 Passenger | [png](Airborne/Passenger/Airbus%20A330-200%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-200%20Passenger.png) |
| Airbus A330-300 Passenger (PW) | [png](Airborne/Passenger/Airbus%20A330-300%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-300%20Passenger%20%28PW%29.png) |
| Airbus A330-300 Passenger (RR) | [png](Airborne/Passenger/Airbus%20A330-300%20Passenger%20%28RR%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-300%20Passenger%20%28RR%29.png) |
| Airbus A330-300 Passenger | [png](Airborne/Passenger/Airbus%20A330-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-300%20Passenger.png) |
| Airbus A330-800neo Passenger | [png](Airborne/Passenger/Airbus%20A330-800neo%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-800neo%20Passenger.png) |
| Airbus A330-900neo Passenger | [png](Airborne/Passenger/Airbus%20A330-900neo%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A330-900neo%20Passenger.png) |
| Airbus A330neo Passenger | [png](Airborne/Passenger/Airbus%20A330neo%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A330neo%20Passenger.png) |
| Airbus A340 Passenger | [png](Airborne/Passenger/Airbus%20A340%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A340%20Passenger.png) |
| Airbus A340-200 Passenger | [png](Airborne/Passenger/Airbus%20A340-200%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A340-200%20Passenger.png) |
| Airbus A340-300 Passenger (A340-300X) | [png](Airborne/Passenger/Airbus%20A340-300%20Passenger%20%28A340-300X%29.png) | [png](On%20the%20ground/Passenger/Airbus%20A340-300%20Passenger%20%28A340-300X%29.png) |
| Airbus A340-300 Passenger | [png](Airborne/Passenger/Airbus%20A340-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A340-300%20Passenger.png) |
| Airbus A340-500 Passenger | [png](Airborne/Passenger/Airbus%20A340-500%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A340-500%20Passenger.png) |
| Airbus A340-600 Passenger | [png](Airborne/Passenger/Airbus%20A340-600%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A340-600%20Passenger.png) |
| Airbus A350 Passenger | [png](Airborne/Passenger/Airbus%20A350%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A350%20Passenger.png) |
| Airbus A350-1000 Passenger | [png](Airborne/Passenger/Airbus%20A350-1000%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A350-1000%20Passenger.png) |
| Airbus A350-800 Passenger | [png](Airborne/Passenger/Airbus%20A350-800%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A350-800%20Passenger.png) |
| Airbus A350-900 Passenger | [png](Airborne/Passenger/Airbus%20A350-900%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A350-900%20Passenger.png) |
| Airbus A380-800 Passenger | [png](Airborne/Passenger/Airbus%20A380-800%20Passenger.png) | [png](On%20the%20ground/Passenger/Airbus%20A380-800%20Passenger.png) |
| Avcraft Aviation Dornier 328JET Passenger | [png](Airborne/Passenger/Avcraft%20Aviation%20Dornier%20328JET%20Passenger.png) | [png](On%20the%20ground/Passenger/Avcraft%20Aviation%20Dornier%20328JET%20Passenger.png) |
| BAE Systems (Avro) RJ Passenger | [png](Airborne/Passenger/BAE%20Systems%20%28Avro%29%20RJ%20Passenger.png) | [png](On%20the%20ground/Passenger/BAE%20Systems%20%28Avro%29%20RJ%20Passenger.png) |
| BAE Systems (Avro) RJ85 Passenger | [png](Airborne/Passenger/BAE%20Systems%20%28Avro%29%20RJ85%20Passenger.png) | [png](On%20the%20ground/Passenger/BAE%20Systems%20%28Avro%29%20RJ85%20Passenger.png) |
| BAE Systems (Avro) RJX85 Passenger | [png](Airborne/Passenger/BAE%20Systems%20%28Avro%29%20RJX85%20Passenger.png) | [png](On%20the%20ground/Passenger/BAE%20Systems%20%28Avro%29%20RJX85%20Passenger.png) |
| BAE Systems (HS) BAe 146 200 Passenger | [png](Airborne/Passenger/BAE%20Systems%20%28HS%29%20BAe%20146%20200%20Passenger.png) | [png](On%20the%20ground/Passenger/BAE%20Systems%20%28HS%29%20BAe%20146%20200%20Passenger.png) |
| BAE Systems (Jetstream) Jetstream 41 Passenger | [png](Airborne/Passenger/BAE%20Systems%20%28Jetstream%29%20Jetstream%2041%20Passenger.png) | [png](On%20the%20ground/Passenger/BAE%20Systems%20%28Jetstream%29%20Jetstream%2041%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-11 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-11%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-11%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-81 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-81%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-81%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-82 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-82%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-82%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-83 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-83%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-83%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-87 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-87%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-87%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-88 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-88%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-88%20Passenger.png) |
| Boeing (McDonnell-Douglas) MD-90-30 Passenger | [png](Airborne/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-90-30%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20%28McDonnell-Douglas%29%20MD-90-30%20Passenger.png) |
| Boeing 717-200 Passenger | [png](Airborne/Passenger/Boeing%20717-200%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20717-200%20Passenger.png) |
| Boeing 737 (CFMI) Passenger | [png](Airborne/Passenger/Boeing%20737%20%28CFMI%29%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20%28CFMI%29%20Passenger.png) |
| Boeing 737 Max 10 Passenger | [png](Airborne/Passenger/Boeing%20737%20Max%2010%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20Max%2010%20Passenger.png) |
| Boeing 737 Max 7 Passenger | [png](Airborne/Passenger/Boeing%20737%20Max%207%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20Max%207%20Passenger.png) |
| Boeing 737 Max 8 Passenger | [png](Airborne/Passenger/Boeing%20737%20Max%208%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20Max%208%20Passenger.png) |
| Boeing 737 Max 9 Passenger | [png](Airborne/Passenger/Boeing%20737%20Max%209%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20Max%209%20Passenger.png) |
| Boeing 737 Max Passenger | [png](Airborne/Passenger/Boeing%20737%20Max%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20Max%20Passenger.png) |
| Boeing 737 NG Passenger | [png](Airborne/Passenger/Boeing%20737%20NG%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737%20NG%20Passenger.png) |
| Boeing 737-300 Passenger (blended winglets) | [png](Airborne/Passenger/Boeing%20737-300%20Passenger%20%28blended%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-300%20Passenger%20%28blended%20winglets%29.png) |
| Boeing 737-300 Passenger | [png](Airborne/Passenger/Boeing%20737-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-300%20Passenger.png) |
| Boeing 737-400 Passenger | [png](Airborne/Passenger/Boeing%20737-400%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-400%20Passenger.png) |
| Boeing 737-500 Passenger (blended winglets) | [png](Airborne/Passenger/Boeing%20737-500%20Passenger%20%28blended%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-500%20Passenger%20%28blended%20winglets%29.png) |
| Boeing 737-500 Passenger | [png](Airborne/Passenger/Boeing%20737-500%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-500%20Passenger.png) |
| Boeing 737-600 Passenger | [png](Airborne/Passenger/Boeing%20737-600%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-600%20Passenger.png) |
| Boeing 737-700 Passenger (no winglets) | [png](Airborne/Passenger/Boeing%20737-700%20Passenger%20%28no%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-700%20Passenger%20%28no%20winglets%29.png) |
| Boeing 737-700 Passenger (split scimitar) | [png](Airborne/Passenger/Boeing%20737-700%20Passenger%20%28split%20scimitar%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-700%20Passenger%20%28split%20scimitar%29.png) |
| Boeing 737-700 Passenger | [png](Airborne/Passenger/Boeing%20737-700%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-700%20Passenger.png) |
| Boeing 737-800 Passenger (blended winglets) | [png](Airborne/Passenger/Boeing%20737-800%20Passenger%20%28blended%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-800%20Passenger%20%28blended%20winglets%29.png) |
| Boeing 737-800 Passenger (no winglets) | [png](Airborne/Passenger/Boeing%20737-800%20Passenger%20%28no%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-800%20Passenger%20%28no%20winglets%29.png) |
| Boeing 737-800 Passenger | [png](Airborne/Passenger/Boeing%20737-800%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-800%20Passenger.png) |
| Boeing 737-900 Passenger (ER, split scimitar) | [png](Airborne/Passenger/Boeing%20737-900%20Passenger%20%28ER%2C%20split%20scimitar%29.png) | [png](On%20the%20ground/Passenger/Boeing%20737-900%20Passenger%20%28ER%2C%20split%20scimitar%29.png) |
| Boeing 737-900 Passenger | [png](Airborne/Passenger/Boeing%20737-900%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20737-900%20Passenger.png) |
| Boeing 747-400 Passenger (PW) | [png](Airborne/Passenger/Boeing%20747-400%20Passenger%20%28PW%29.png) | [png](On%20the%20ground/Passenger/Boeing%20747-400%20Passenger%20%28PW%29.png) |
| Boeing 747-400 Passenger (RR) | [png](Airborne/Passenger/Boeing%20747-400%20Passenger%20%28RR%29.png) | [png](On%20the%20ground/Passenger/Boeing%20747-400%20Passenger%20%28RR%29.png) |
| Boeing 747-400 Passenger | [png](Airborne/Passenger/Boeing%20747-400%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20747-400%20Passenger.png) |
| Boeing 747-8 Passenger | [png](Airborne/Passenger/Boeing%20747-8%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20747-8%20Passenger.png) |
| Boeing 757-200 Passenger (PW, no winglets) | [png](Airborne/Passenger/Boeing%20757-200%20Passenger%20%28PW%2C%20no%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20757-200%20Passenger%20%28PW%2C%20no%20winglets%29.png) |
| Boeing 757-200 Passenger (RR, no winglets) | [png](Airborne/Passenger/Boeing%20757-200%20Passenger%20%28RR%2C%20no%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20757-200%20Passenger%20%28RR%2C%20no%20winglets%29.png) |
| Boeing 757-200 Passenger (RR, winglets) | [png](Airborne/Passenger/Boeing%20757-200%20Passenger%20%28RR%2C%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20757-200%20Passenger%20%28RR%2C%20winglets%29.png) |
| Boeing 757-200 Passenger | [png](Airborne/Passenger/Boeing%20757-200%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20757-200%20Passenger.png) |
| Boeing 757-300 Passenger | [png](Airborne/Passenger/Boeing%20757-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20757-300%20Passenger.png) |
| Boeing 767-200 Passenger (bare metal) | [png](Airborne/Passenger/Boeing%20767-200%20Passenger%20%28bare%20metal%29.png) | [png](On%20the%20ground/Passenger/Boeing%20767-200%20Passenger%20%28bare%20metal%29.png) |
| Boeing 767-200 Passenger | [png](Airborne/Passenger/Boeing%20767-200%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20767-200%20Passenger.png) |
| Boeing 767-300 Passenger (no winglets) | [png](Airborne/Passenger/Boeing%20767-300%20Passenger%20%28no%20winglets%29.png) | [png](On%20the%20ground/Passenger/Boeing%20767-300%20Passenger%20%28no%20winglets%29.png) |
| Boeing 767-300 Passenger | [png](Airborne/Passenger/Boeing%20767-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20767-300%20Passenger.png) |
| Boeing 767-400 Passenger | [png](Airborne/Passenger/Boeing%20767-400%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20767-400%20Passenger.png) |
| Boeing 777 Passenger | [png](Airborne/Passenger/Boeing%20777%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20777%20Passenger.png) |
| Boeing 777-200 Passenger | [png](Airborne/Passenger/Boeing%20777-200%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20777-200%20Passenger.png) |
| Boeing 777-300 Passenger | [png](Airborne/Passenger/Boeing%20777-300%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20777-300%20Passenger.png) |
| Boeing 777-8 Passenger (folded wingtips) | [png](Airborne/Passenger/Boeing%20777-8%20Passenger%20%28folded%20wingtips%29.png) | [png](On%20the%20ground/Passenger/Boeing%20777-8%20Passenger%20%28folded%20wingtips%29.png) |
| Boeing 777-8 Passenger | [png](Airborne/Passenger/Boeing%20777-8%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20777-8%20Passenger.png) |
| Boeing 777-8-9 Passenger | [png](Airborne/Passenger/Boeing%20777-8-9%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20777-8-9%20Passenger.png) |
| Boeing 777-9 Passenger (folded wingtips) | [png](Airborne/Passenger/Boeing%20777-9%20Passenger%20%28folded%20wingtips%29.png) | [png](On%20the%20ground/Passenger/Boeing%20777-9%20Passenger%20%28folded%20wingtips%29.png) |
| Boeing 777-9 Passenger | [png](Airborne/Passenger/Boeing%20777-9%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20777-9%20Passenger.png) |
| Boeing 787 Passenger | [png](Airborne/Passenger/Boeing%20787%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20787%20Passenger.png) |
| Boeing 787-10 Passenger | [png](Airborne/Passenger/Boeing%20787-10%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20787-10%20Passenger.png) |
| Boeing 787-8 Passenger | [png](Airborne/Passenger/Boeing%20787-8%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20787-8%20Passenger.png) |
| Boeing 787-9 Passenger | [png](Airborne/Passenger/Boeing%20787-9%20Passenger.png) | [png](On%20the%20ground/Passenger/Boeing%20787-9%20Passenger.png) |
| Bombardier (Canadair) CRJ100 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20CRJ100%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20CRJ100%20Passenger.png) |
| Bombardier (Canadair) CRJ1000 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20CRJ1000%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20CRJ1000%20Passenger.png) |
| Bombardier (Canadair) CRJ200 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20CRJ200%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20CRJ200%20Passenger.png) |
| Bombardier (Canadair) CRJ700 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20CRJ700%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20CRJ700%20Passenger.png) |
| Bombardier (Canadair) CRJ705 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20CRJ705%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20CRJ705%20Passenger.png) |
| Bombardier (Canadair) CRJ900 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20CRJ900%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20CRJ900%20Passenger.png) |
| Bombardier (Canadair) Global 5000 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20Global%205000%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20Global%205000%20Passenger.png) |
| Bombardier (Canadair) Global 5500 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20Global%205500%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20Global%205500%20Passenger.png) |
| Bombardier (Canadair) Global 7500 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20Global%207500%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20Global%207500%20Passenger.png) |
| Bombardier (Canadair) Global 8000 Passenger | [png](Airborne/Passenger/Bombardier%20%28Canadair%29%20Global%208000%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Canadair%29%20Global%208000%20Passenger.png) |
| Bombardier (Learjet) Learjet 45 Passenger | [png](Airborne/Passenger/Bombardier%20%28Learjet%29%20Learjet%2045%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Learjet%29%20Learjet%2045%20Passenger.png) |
| Bombardier (Learjet) Learjet 60 Passenger | [png](Airborne/Passenger/Bombardier%20%28Learjet%29%20Learjet%2060%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Learjet%29%20Learjet%2060%20Passenger.png) |
| Bombardier (Learjet) Learjet 75 Liberty Passenger | [png](Airborne/Passenger/Bombardier%20%28Learjet%29%20Learjet%2075%20Liberty%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Learjet%29%20Learjet%2075%20Liberty%20Passenger.png) |
| Bombardier (Learjet) Learjet 75 Passenger | [png](Airborne/Passenger/Bombardier%20%28Learjet%29%20Learjet%2075%20Passenger.png) | [png](On%20the%20ground/Passenger/Bombardier%20%28Learjet%29%20Learjet%2075%20Passenger.png) |
| COMAC C909 Passenger | [png](Airborne/Passenger/COMAC%20C909%20Passenger.png) | [png](On%20the%20ground/Passenger/COMAC%20C909%20Passenger.png) |
| COMAC C919 Passenger | [png](Airborne/Passenger/COMAC%20C919%20Passenger.png) | [png](On%20the%20ground/Passenger/COMAC%20C919%20Passenger.png) |
| COMAC C919 Plateau Passenger | [png](Airborne/Passenger/COMAC%20C919%20Plateau%20Passenger.png) | [png](On%20the%20ground/Passenger/COMAC%20C919%20Plateau%20Passenger.png) |
| COMAC C919ER Passenger | [png](Airborne/Passenger/COMAC%20C919ER%20Passenger.png) | [png](On%20the%20ground/Passenger/COMAC%20C919ER%20Passenger.png) |
| Dassault Falcon 50 Passenger (winglets) | [png](Airborne/Passenger/Dassault%20Falcon%2050%20Passenger%20%28winglets%29.png) | [png](On%20the%20ground/Passenger/Dassault%20Falcon%2050%20Passenger%20%28winglets%29.png) |
| Dassault Falcon 50 Passenger | [png](Airborne/Passenger/Dassault%20Falcon%2050%20Passenger.png) | [png](On%20the%20ground/Passenger/Dassault%20Falcon%2050%20Passenger.png) |
| De Havilland Canada DHC-8-100 Passenger | [png](Airborne/Passenger/De%20Havilland%20Canada%20DHC-8-100%20Passenger.png) | [png](On%20the%20ground/Passenger/De%20Havilland%20Canada%20DHC-8-100%20Passenger.png) |
| De Havilland Canada DHC-8-200 Passenger | [png](Airborne/Passenger/De%20Havilland%20Canada%20DHC-8-200%20Passenger.png) | [png](On%20the%20ground/Passenger/De%20Havilland%20Canada%20DHC-8-200%20Passenger.png) |
| De Havilland Canada DHC-8-300 Passenger | [png](Airborne/Passenger/De%20Havilland%20Canada%20DHC-8-300%20Passenger.png) | [png](On%20the%20ground/Passenger/De%20Havilland%20Canada%20DHC-8-300%20Passenger.png) |
| De Havilland Canada DHC-8-400 (Q400) Passenger | [png](Airborne/Passenger/De%20Havilland%20Canada%20DHC-8-400%20%28Q400%29%20Passenger.png) | [png](On%20the%20ground/Passenger/De%20Havilland%20Canada%20DHC-8-400%20%28Q400%29%20Passenger.png) |
| De Havilland Canada Short 360 (SD3-60) 300 Passenger | [png](Airborne/Passenger/De%20Havilland%20Canada%20Short%20360%20%28SD3-60%29%20300%20Passenger.png) | [png](On%20the%20ground/Passenger/De%20Havilland%20Canada%20Short%20360%20%28SD3-60%29%20300%20Passenger.png) |
| Deutsche Aircraft Dornier 328 100 Passenger | [png](Airborne/Passenger/Deutsche%20Aircraft%20Dornier%20328%20100%20Passenger.png) | [png](On%20the%20ground/Passenger/Deutsche%20Aircraft%20Dornier%20328%20100%20Passenger.png) |
| Deutsche Aircraft Dornier 328JET Passenger | [png](Airborne/Passenger/Deutsche%20Aircraft%20Dornier%20328JET%20Passenger.png) | [png](On%20the%20ground/Passenger/Deutsche%20Aircraft%20Dornier%20328JET%20Passenger.png) |
| Embraer E175 E2 Passenger | [png](Airborne/Passenger/Embraer%20E175%20E2%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20E175%20E2%20Passenger.png) |
| Embraer E175 Passenger (old winglets) | [png](Airborne/Passenger/Embraer%20E175%20Passenger%20%28old%20winglets%29.png) | [png](On%20the%20ground/Passenger/Embraer%20E175%20Passenger%20%28old%20winglets%29.png) |
| Embraer E175 Passenger | [png](Airborne/Passenger/Embraer%20E175%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20E175%20Passenger.png) |
| Embraer E190 E2 Passenger | [png](Airborne/Passenger/Embraer%20E190%20E2%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20E190%20E2%20Passenger.png) |
| Embraer E190 Passenger | [png](Airborne/Passenger/Embraer%20E190%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20E190%20Passenger.png) |
| Embraer E195 E2 Passenger | [png](Airborne/Passenger/Embraer%20E195%20E2%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20E195%20E2%20Passenger.png) |
| Embraer E195 Passenger | [png](Airborne/Passenger/Embraer%20E195%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20E195%20Passenger.png) |
| Embraer EMB-120 Passenger | [png](Airborne/Passenger/Embraer%20EMB-120%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20EMB-120%20Passenger.png) |
| Embraer ERJ-135 Passenger | [png](Airborne/Passenger/Embraer%20ERJ-135%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20ERJ-135%20Passenger.png) |
| Embraer ERJ-140 Passenger | [png](Airborne/Passenger/Embraer%20ERJ-140%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20ERJ-140%20Passenger.png) |
| Embraer ERJ-145 Passenger (XR) | [png](Airborne/Passenger/Embraer%20ERJ-145%20Passenger%20%28XR%29.png) | [png](On%20the%20ground/Passenger/Embraer%20ERJ-145%20Passenger%20%28XR%29.png) |
| Embraer ERJ-145 Passenger | [png](Airborne/Passenger/Embraer%20ERJ-145%20Passenger.png) | [png](On%20the%20ground/Passenger/Embraer%20ERJ-145%20Passenger.png) |
| Fokker Fokker 100 Passenger | [png](Airborne/Passenger/Fokker%20Fokker%20100%20Passenger.png) | [png](On%20the%20ground/Passenger/Fokker%20Fokker%20100%20Passenger.png) |
| Fokker Fokker 70 Passenger | [png](Airborne/Passenger/Fokker%20Fokker%2070%20Passenger.png) | [png](On%20the%20ground/Passenger/Fokker%20Fokker%2070%20Passenger.png) |
| Gulfstream Gulfstream G500 (Classic) Passenger | [png](Airborne/Passenger/Gulfstream%20Gulfstream%20G500%20%28Classic%29%20Passenger.png) | [png](On%20the%20ground/Passenger/Gulfstream%20Gulfstream%20G500%20%28Classic%29%20Passenger.png) |
| Gulfstream Gulfstream G550 Passenger | [png](Airborne/Passenger/Gulfstream%20Gulfstream%20G550%20Passenger.png) | [png](On%20the%20ground/Passenger/Gulfstream%20Gulfstream%20G550%20Passenger.png) |
| Gulfstream Gulfstream G650 Passenger | [png](Airborne/Passenger/Gulfstream%20Gulfstream%20G650%20Passenger.png) | [png](On%20the%20ground/Passenger/Gulfstream%20Gulfstream%20G650%20Passenger.png) |
| Harbin Embraer ERJ-135 Passenger | [png](Airborne/Passenger/Harbin%20Embraer%20ERJ-135%20Passenger.png) | [png](On%20the%20ground/Passenger/Harbin%20Embraer%20ERJ-135%20Passenger.png) |
| Harbin Embraer ERJ-145 Passenger | [png](Airborne/Passenger/Harbin%20Embraer%20ERJ-145%20Passenger.png) | [png](On%20the%20ground/Passenger/Harbin%20Embraer%20ERJ-145%20Passenger.png) |
| Mitsubishi CRJ100 Passenger | [png](Airborne/Passenger/Mitsubishi%20CRJ100%20Passenger.png) | [png](On%20the%20ground/Passenger/Mitsubishi%20CRJ100%20Passenger.png) |
| Mitsubishi CRJ1000 Passenger | [png](Airborne/Passenger/Mitsubishi%20CRJ1000%20Passenger.png) | [png](On%20the%20ground/Passenger/Mitsubishi%20CRJ1000%20Passenger.png) |
| Mitsubishi CRJ200 Passenger | [png](Airborne/Passenger/Mitsubishi%20CRJ200%20Passenger.png) | [png](On%20the%20ground/Passenger/Mitsubishi%20CRJ200%20Passenger.png) |
| Mitsubishi CRJ700 Passenger | [png](Airborne/Passenger/Mitsubishi%20CRJ700%20Passenger.png) | [png](On%20the%20ground/Passenger/Mitsubishi%20CRJ700%20Passenger.png) |
| Mitsubishi CRJ705 Passenger | [png](Airborne/Passenger/Mitsubishi%20CRJ705%20Passenger.png) | [png](On%20the%20ground/Passenger/Mitsubishi%20CRJ705%20Passenger.png) |
| Mitsubishi CRJ900 Passenger | [png](Airborne/Passenger/Mitsubishi%20CRJ900%20Passenger.png) | [png](On%20the%20ground/Passenger/Mitsubishi%20CRJ900%20Passenger.png) |
| Saab Saab 340 B Passenger | [png](Airborne/Passenger/Saab%20Saab%20340%20B%20Passenger.png) | [png](On%20the%20ground/Passenger/Saab%20Saab%20340%20B%20Passenger.png) |
| TRJet Dornier 328JET Passenger | [png](Airborne/Passenger/TRJet%20Dornier%20328JET%20Passenger.png) | [png](On%20the%20ground/Passenger/TRJet%20Dornier%20328JET%20Passenger.png) |
| Textron Aviation (Beechcraft) Beech 1900 D Passenger | [png](Airborne/Passenger/Textron%20Aviation%20%28Beechcraft%29%20Beech%201900%20D%20Passenger.png) | [png](On%20the%20ground/Passenger/Textron%20Aviation%20%28Beechcraft%29%20Beech%201900%20D%20Passenger.png) |
| Textron Aviation (Beechcraft) King Air 200 Passenger | [png](Airborne/Passenger/Textron%20Aviation%20%28Beechcraft%29%20King%20Air%20200%20Passenger.png) | [png](On%20the%20ground/Passenger/Textron%20Aviation%20%28Beechcraft%29%20King%20Air%20200%20Passenger.png) |
| Textron Aviation (Cessna) 750 Citation X Passenger (winglets) | [png](Airborne/Passenger/Textron%20Aviation%20%28Cessna%29%20750%20Citation%20X%20Passenger%20%28winglets%29.png) | [png](On%20the%20ground/Passenger/Textron%20Aviation%20%28Cessna%29%20750%20Citation%20X%20Passenger%20%28winglets%29.png) |
| Textron Aviation (Cessna) 750 Citation X Passenger | [png](Airborne/Passenger/Textron%20Aviation%20%28Cessna%29%20750%20Citation%20X%20Passenger.png) | [png](On%20the%20ground/Passenger/Textron%20Aviation%20%28Cessna%29%20750%20Citation%20X%20Passenger.png) |
| Textron Aviation (Cessna) Cessna 208B Caravan Passenger | [png](Airborne/Passenger/Textron%20Aviation%20%28Cessna%29%20Cessna%20208B%20Caravan%20Passenger.png) | [png](On%20the%20ground/Passenger/Textron%20Aviation%20%28Cessna%29%20Cessna%20208B%20Caravan%20Passenger.png) |
| UAC (Irkut) MC-21 Passenger | [png](Airborne/Passenger/UAC%20%28Irkut%29%20MC-21%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Irkut%29%20MC-21%20Passenger.png) |
| UAC (Irkut) MC-21-300 Passenger | [png](Airborne/Passenger/UAC%20%28Irkut%29%20MC-21-300%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Irkut%29%20MC-21-300%20Passenger.png) |
| UAC (Irkut) MC-21-310 Passenger | [png](Airborne/Passenger/UAC%20%28Irkut%29%20MC-21-310%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Irkut%29%20MC-21-310%20Passenger.png) |
| UAC (Sukhoi) Superjet 100 95 Passenger | [png](Airborne/Passenger/UAC%20%28Sukhoi%29%20Superjet%20100%2095%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Sukhoi%29%20Superjet%20100%2095%20Passenger.png) |
| UAC (Sukhoi) Superjet 100 Passenger | [png](Airborne/Passenger/UAC%20%28Sukhoi%29%20Superjet%20100%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Sukhoi%29%20Superjet%20100%20Passenger.png) |
| UAC (Sukhoi) Superjet 100 SBJ Passenger | [png](Airborne/Passenger/UAC%20%28Sukhoi%29%20Superjet%20100%20SBJ%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Sukhoi%29%20Superjet%20100%20SBJ%20Passenger.png) |
| UAC (Sukhoi) Superjet SJ-100 Passenger | [png](Airborne/Passenger/UAC%20%28Sukhoi%29%20Superjet%20SJ-100%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Sukhoi%29%20Superjet%20SJ-100%20Passenger.png) |
| UAC (Tupolev) Tu-154M Passenger | [png](Airborne/Passenger/UAC%20%28Tupolev%29%20Tu-154M%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Tupolev%29%20Tu-154M%20Passenger.png) |
| UAC (Tupolev) Tu-204 Passenger | [png](Airborne/Passenger/UAC%20%28Tupolev%29%20Tu-204%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Tupolev%29%20Tu-204%20Passenger.png) |
| UAC (Tupolev) Tu-204-100 Passenger | [png](Airborne/Passenger/UAC%20%28Tupolev%29%20Tu-204-100%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Tupolev%29%20Tu-204-100%20Passenger.png) |
| UAC (Tupolev) Tu-204-120 Passenger | [png](Airborne/Passenger/UAC%20%28Tupolev%29%20Tu-204-120%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Tupolev%29%20Tu-204-120%20Passenger.png) |
| UAC (Tupolev) Tu-214 Passenger | [png](Airborne/Passenger/UAC%20%28Tupolev%29%20Tu-214%20Passenger.png) | [png](On%20the%20ground/Passenger/UAC%20%28Tupolev%29%20Tu-214%20Passenger.png) |
| Viking Air Short 360 (SD3-60) 300 Passenger | [png](Airborne/Passenger/Viking%20Air%20Short%20360%20%28SD3-60%29%20300%20Passenger.png) | [png](On%20the%20ground/Passenger/Viking%20Air%20Short%20360%20%28SD3-60%29%20300%20Passenger.png) |

</details>

<details>
<summary>Cargo (72)</summary>

| Aircraft type | Airborne | On the ground |
|---|---|---|
| ATR ATR 42 300 Cargo | [png](Airborne/Cargo/ATR%20ATR%2042%20300%20Cargo.png) | [png](On%20the%20ground/Cargo/ATR%20ATR%2042%20300%20Cargo.png) |
| ATR ATR 42 500 Cargo | [png](Airborne/Cargo/ATR%20ATR%2042%20500%20Cargo.png) | [png](On%20the%20ground/Cargo/ATR%20ATR%2042%20500%20Cargo.png) |
| ATR ATR 72 200 Cargo | [png](Airborne/Cargo/ATR%20ATR%2072%20200%20Cargo.png) | [png](On%20the%20ground/Cargo/ATR%20ATR%2072%20200%20Cargo.png) |
| ATR ATR 72 500 Cargo | [png](Airborne/Cargo/ATR%20ATR%2072%20500%20Cargo.png) | [png](On%20the%20ground/Cargo/ATR%20ATR%2072%20500%20Cargo.png) |
| ATR ATR 72 600 Cargo | [png](Airborne/Cargo/ATR%20ATR%2072%20600%20Cargo.png) | [png](On%20the%20ground/Cargo/ATR%20ATR%2072%20600%20Cargo.png) |
| Airbus A300-600 Cargo | [png](Airborne/Cargo/Airbus%20A300-600%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A300-600%20Cargo.png) |
| Airbus A310 Cargo | [png](Airborne/Cargo/Airbus%20A310%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A310%20Cargo.png) |
| Airbus A320 Cargo | [png](Airborne/Cargo/Airbus%20A320%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A320%20Cargo.png) |
| Airbus A321 Cargo | [png](Airborne/Cargo/Airbus%20A321%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A321%20Cargo.png) |
| Airbus A330-200 Cargo (PW) | [png](Airborne/Cargo/Airbus%20A330-200%20Cargo%20%28PW%29.png) | [png](On%20the%20ground/Cargo/Airbus%20A330-200%20Cargo%20%28PW%29.png) |
| Airbus A330-200 Cargo | [png](Airborne/Cargo/Airbus%20A330-200%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A330-200%20Cargo.png) |
| Airbus A330-300 Cargo | [png](Airborne/Cargo/Airbus%20A330-300%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A330-300%20Cargo.png) |
| Airbus A340-300 Cargo | [png](Airborne/Cargo/Airbus%20A340-300%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A340-300%20Cargo.png) |
| Airbus A340-600 Cargo | [png](Airborne/Cargo/Airbus%20A340-600%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A340-600%20Cargo.png) |
| Airbus A350F Cargo | [png](Airborne/Cargo/Airbus%20A350F%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A350F%20Cargo.png) |
| Airbus A380-800 Cargo | [png](Airborne/Cargo/Airbus%20A380-800%20Cargo.png) | [png](On%20the%20ground/Cargo/Airbus%20A380-800%20Cargo.png) |
| BAE Systems (HS) BAe 146 200 Cargo | [png](Airborne/Cargo/BAE%20Systems%20%28HS%29%20BAe%20146%20200%20Cargo.png) | [png](On%20the%20ground/Cargo/BAE%20Systems%20%28HS%29%20BAe%20146%20200%20Cargo.png) |
| Boeing (McDonnell-Douglas) MD-11 Cargo | [png](Airborne/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-11%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-11%20Cargo.png) |
| Boeing (McDonnell-Douglas) MD-82 Cargo | [png](Airborne/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-82%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-82%20Cargo.png) |
| Boeing (McDonnell-Douglas) MD-83 Cargo | [png](Airborne/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-83%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-83%20Cargo.png) |
| Boeing (McDonnell-Douglas) MD-88 Cargo | [png](Airborne/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-88%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20%28McDonnell-Douglas%29%20MD-88%20Cargo.png) |
| Boeing 737-300 Cargo | [png](Airborne/Cargo/Boeing%20737-300%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20737-300%20Cargo.png) |
| Boeing 737-400 Cargo (Combi) | [png](Airborne/Cargo/Boeing%20737-400%20Cargo%20%28Combi%29.png) | [png](On%20the%20ground/Cargo/Boeing%20737-400%20Cargo%20%28Combi%29.png) |
| Boeing 737-500 Cargo | [png](Airborne/Cargo/Boeing%20737-500%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20737-500%20Cargo.png) |
| Boeing 737-700 Cargo | [png](Airborne/Cargo/Boeing%20737-700%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20737-700%20Cargo.png) |
| Boeing 737-800 Cargo | [png](Airborne/Cargo/Boeing%20737-800%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20737-800%20Cargo.png) |
| Boeing 747-200 Cargo (GE) | [png](Airborne/Cargo/Boeing%20747-200%20Cargo%20%28GE%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-200%20Cargo%20%28GE%29.png) |
| Boeing 747-200 Cargo (GE, polished engines) | [png](Airborne/Cargo/Boeing%20747-200%20Cargo%20%28GE%2C%20polished%20engines%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-200%20Cargo%20%28GE%2C%20polished%20engines%29.png) |
| Boeing 747-200 Cargo (PW, polished engines) | [png](Airborne/Cargo/Boeing%20747-200%20Cargo%20%28PW%2C%20polished%20engines%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-200%20Cargo%20%28PW%2C%20polished%20engines%29.png) |
| Boeing 747-200 Cargo (RR) | [png](Airborne/Cargo/Boeing%20747-200%20Cargo%20%28RR%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-200%20Cargo%20%28RR%29.png) |
| Boeing 747-200 Cargo (RR, polished engines) | [png](Airborne/Cargo/Boeing%20747-200%20Cargo%20%28RR%2C%20polished%20engines%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-200%20Cargo%20%28RR%2C%20polished%20engines%29.png) |
| Boeing 747-200 Cargo | [png](Airborne/Cargo/Boeing%20747-200%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20747-200%20Cargo.png) |
| Boeing 747-300 Cargo (PW) | [png](Airborne/Cargo/Boeing%20747-300%20Cargo%20%28PW%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-300%20Cargo%20%28PW%29.png) |
| Boeing 747-300 Cargo (RR) | [png](Airborne/Cargo/Boeing%20747-300%20Cargo%20%28RR%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-300%20Cargo%20%28RR%29.png) |
| Boeing 747-300 Cargo | [png](Airborne/Cargo/Boeing%20747-300%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20747-300%20Cargo.png) |
| Boeing 747-400 Cargo (BCF) | [png](Airborne/Cargo/Boeing%20747-400%20Cargo%20%28BCF%29.png) | [png](On%20the%20ground/Cargo/Boeing%20747-400%20Cargo%20%28BCF%29.png) |
| Boeing 747-400 Cargo | [png](Airborne/Cargo/Boeing%20747-400%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20747-400%20Cargo.png) |
| Boeing 747-8 Cargo | [png](Airborne/Cargo/Boeing%20747-8%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20747-8%20Cargo.png) |
| Boeing 757-200 Cargo (PF-PCF, PW) | [png](Airborne/Cargo/Boeing%20757-200%20Cargo%20%28PF-PCF%2C%20PW%29.png) | [png](On%20the%20ground/Cargo/Boeing%20757-200%20Cargo%20%28PF-PCF%2C%20PW%29.png) |
| Boeing 757-200 Cargo (PF-PCF, RR) | [png](Airborne/Cargo/Boeing%20757-200%20Cargo%20%28PF-PCF%2C%20RR%29.png) | [png](On%20the%20ground/Cargo/Boeing%20757-200%20Cargo%20%28PF-PCF%2C%20RR%29.png) |
| Boeing 757-200 Cargo (SF, RR) | [png](Airborne/Cargo/Boeing%20757-200%20Cargo%20%28SF%2C%20RR%29.png) | [png](On%20the%20ground/Cargo/Boeing%20757-200%20Cargo%20%28SF%2C%20RR%29.png) |
| Boeing 757-200 Cargo | [png](Airborne/Cargo/Boeing%20757-200%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20757-200%20Cargo.png) |
| Boeing 767-200 Cargo | [png](Airborne/Cargo/Boeing%20767-200%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20767-200%20Cargo.png) |
| Boeing 767-300 Cargo (winglets) | [png](Airborne/Cargo/Boeing%20767-300%20Cargo%20%28winglets%29.png) | [png](On%20the%20ground/Cargo/Boeing%20767-300%20Cargo%20%28winglets%29.png) |
| Boeing 767-300 Cargo | [png](Airborne/Cargo/Boeing%20767-300%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20767-300%20Cargo.png) |
| Boeing 777-200 Cargo | [png](Airborne/Cargo/Boeing%20777-200%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20777-200%20Cargo.png) |
| Boeing 777-300 Cargo | [png](Airborne/Cargo/Boeing%20777-300%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20777-300%20Cargo.png) |
| Boeing 777-8 Cargo | [png](Airborne/Cargo/Boeing%20777-8%20Cargo.png) | [png](On%20the%20ground/Cargo/Boeing%20777-8%20Cargo.png) |
| Bombardier (Canadair) CRJ100 Cargo | [png](Airborne/Cargo/Bombardier%20%28Canadair%29%20CRJ100%20Cargo.png) | [png](On%20the%20ground/Cargo/Bombardier%20%28Canadair%29%20CRJ100%20Cargo.png) |
| Bombardier (Canadair) CRJ200 Cargo | [png](Airborne/Cargo/Bombardier%20%28Canadair%29%20CRJ200%20Cargo.png) | [png](On%20the%20ground/Cargo/Bombardier%20%28Canadair%29%20CRJ200%20Cargo.png) |
| Bombardier (Learjet) Learjet 45 Cargo | [png](Airborne/Cargo/Bombardier%20%28Learjet%29%20Learjet%2045%20Cargo.png) | [png](On%20the%20ground/Cargo/Bombardier%20%28Learjet%29%20Learjet%2045%20Cargo.png) |
| COMAC C909 Cargo | [png](Airborne/Cargo/COMAC%20C909%20Cargo.png) | [png](On%20the%20ground/Cargo/COMAC%20C909%20Cargo.png) |
| De Havilland Canada DHC-8-100 Cargo | [png](Airborne/Cargo/De%20Havilland%20Canada%20DHC-8-100%20Cargo.png) | [png](On%20the%20ground/Cargo/De%20Havilland%20Canada%20DHC-8-100%20Cargo.png) |
| De Havilland Canada DHC-8-200 Cargo | [png](Airborne/Cargo/De%20Havilland%20Canada%20DHC-8-200%20Cargo.png) | [png](On%20the%20ground/Cargo/De%20Havilland%20Canada%20DHC-8-200%20Cargo.png) |
| De Havilland Canada DHC-8-300 Cargo | [png](Airborne/Cargo/De%20Havilland%20Canada%20DHC-8-300%20Cargo.png) | [png](On%20the%20ground/Cargo/De%20Havilland%20Canada%20DHC-8-300%20Cargo.png) |
| De Havilland Canada DHC-8-400 (Q400) Cargo | [png](Airborne/Cargo/De%20Havilland%20Canada%20DHC-8-400%20%28Q400%29%20Cargo.png) | [png](On%20the%20ground/Cargo/De%20Havilland%20Canada%20DHC-8-400%20%28Q400%29%20Cargo.png) |
| De Havilland Canada Short 360 (SD3-60) 300 Cargo | [png](Airborne/Cargo/De%20Havilland%20Canada%20Short%20360%20%28SD3-60%29%20300%20Cargo.png) | [png](On%20the%20ground/Cargo/De%20Havilland%20Canada%20Short%20360%20%28SD3-60%29%20300%20Cargo.png) |
| Deutsche Aircraft Dornier 328 100 Cargo | [png](Airborne/Cargo/Deutsche%20Aircraft%20Dornier%20328%20100%20Cargo.png) | [png](On%20the%20ground/Cargo/Deutsche%20Aircraft%20Dornier%20328%20100%20Cargo.png) |
| Embraer E190 Cargo | [png](Airborne/Cargo/Embraer%20E190%20Cargo.png) | [png](On%20the%20ground/Cargo/Embraer%20E190%20Cargo.png) |
| Embraer E195 Cargo | [png](Airborne/Cargo/Embraer%20E195%20Cargo.png) | [png](On%20the%20ground/Cargo/Embraer%20E195%20Cargo.png) |
| Embraer EMB-120 Cargo | [png](Airborne/Cargo/Embraer%20EMB-120%20Cargo.png) | [png](On%20the%20ground/Cargo/Embraer%20EMB-120%20Cargo.png) |
| Mitsubishi CRJ100 Cargo | [png](Airborne/Cargo/Mitsubishi%20CRJ100%20Cargo.png) | [png](On%20the%20ground/Cargo/Mitsubishi%20CRJ100%20Cargo.png) |
| Mitsubishi CRJ200 Cargo | [png](Airborne/Cargo/Mitsubishi%20CRJ200%20Cargo.png) | [png](On%20the%20ground/Cargo/Mitsubishi%20CRJ200%20Cargo.png) |
| Mitsubishi CRJ700 Cargo | [png](Airborne/Cargo/Mitsubishi%20CRJ700%20Cargo.png) | [png](On%20the%20ground/Cargo/Mitsubishi%20CRJ700%20Cargo.png) |
| Saab Saab 340 A Cargo | [png](Airborne/Cargo/Saab%20Saab%20340%20A%20Cargo.png) | [png](On%20the%20ground/Cargo/Saab%20Saab%20340%20A%20Cargo.png) |
| Saab Saab 340 B Cargo | [png](Airborne/Cargo/Saab%20Saab%20340%20B%20Cargo.png) | [png](On%20the%20ground/Cargo/Saab%20Saab%20340%20B%20Cargo.png) |
| Textron Aviation (Beechcraft) Beech 1900 D Cargo | [png](Airborne/Cargo/Textron%20Aviation%20%28Beechcraft%29%20Beech%201900%20D%20Cargo.png) | [png](On%20the%20ground/Cargo/Textron%20Aviation%20%28Beechcraft%29%20Beech%201900%20D%20Cargo.png) |
| Textron Aviation (Beechcraft) King Air 200 Cargo | [png](Airborne/Cargo/Textron%20Aviation%20%28Beechcraft%29%20King%20Air%20200%20Cargo.png) | [png](On%20the%20ground/Cargo/Textron%20Aviation%20%28Beechcraft%29%20King%20Air%20200%20Cargo.png) |
| Textron Aviation (Cessna) Cessna 208B Caravan Cargo | [png](Airborne/Cargo/Textron%20Aviation%20%28Cessna%29%20Cessna%20208B%20Caravan%20Cargo.png) | [png](On%20the%20ground/Cargo/Textron%20Aviation%20%28Cessna%29%20Cessna%20208B%20Caravan%20Cargo.png) |
| UAC (Tupolev) Tu-204-100 Cargo | [png](Airborne/Cargo/UAC%20%28Tupolev%29%20Tu-204-100%20Cargo.png) | [png](On%20the%20ground/Cargo/UAC%20%28Tupolev%29%20Tu-204-100%20Cargo.png) |
| UAC (Tupolev) Tu-204-120 Cargo | [png](Airborne/Cargo/UAC%20%28Tupolev%29%20Tu-204-120%20Cargo.png) | [png](On%20the%20ground/Cargo/UAC%20%28Tupolev%29%20Tu-204-120%20Cargo.png) |
| Viking Air Short 360 (SD3-60) 300 Cargo | [png](Airborne/Cargo/Viking%20Air%20Short%20360%20%28SD3-60%29%20300%20Cargo.png) | [png](On%20the%20ground/Cargo/Viking%20Air%20Short%20360%20%28SD3-60%29%20300%20Cargo.png) |

</details>
