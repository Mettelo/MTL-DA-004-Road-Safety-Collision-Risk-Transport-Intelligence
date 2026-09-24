# Data Workspace — MTL-DA-004

## Dataset

**Department for Transport — Road Safety Open Data (STATS19)**

The dataset contains record-level information on personal-injury road collisions reported to police in Great Britain, the vehicles involved and resulting casualties.

## Recommended Project Window

Use the **latest 5 years of final validated data** rather than the complete 1979-to-latest archive.

At project creation, the latest final validated year is **2025**.

Recommended files:

- Road Safety Data — Collisions — last 5 years
- Road Safety Data — Vehicles — last 5 years
- Road Safety Data — Casualties — last 5 years

## Official Source

https://www.gov.uk/government/statistical-data-sets/road-safety-open-data

## Supporting Guidance

Use the official STATS19 data guide/code list supplied by the Department for Transport.

Many fields are coded numerically and must be interpreted through the official guidance.

## Licence

Open Government Licence.

Retain attribution in repository documentation and final outputs.

## Folder Structure

```text
data/
├── README.md
├── raw/
├── reference/
└── metadata/
```

## raw/

Store downloaded source files here where practical.

Expected logical datasets:
- collisions;
- vehicles;
- casualties.

If file size or team workflow makes direct Git storage unsuitable, keep the raw files gitignored and document exact acquisition steps.

## reference/

Store:
- STATS19 data guide;
- code/value mappings;
- licence notes;
- approved supporting documentation.

## metadata/

Store:
- provenance;
- file inventory;
- schema notes;
- data dictionary;
- year coverage;
- known revisions/limitations.

## Team Repository Data Structure

Each team should use:

```text
data/
├── README.md
├── raw/
└── processed/
```

Raw source data must remain unchanged.

The team's `data/README.md` must explain exactly how a Mettelo reviewer obtains and prepares the raw data.
