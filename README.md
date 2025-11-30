# Industries Database

A comprehensive database of all industries and sub-industries worldwide. This repository is designed to serve as an exhaustive reference for industry classification and is tied directly to the [Foundation](../foundation) repository.

## Purpose

This repository contains structured data about:
- **Industries**: Major economic sectors and industry groups
- **Sub-Industries**: Detailed breakdowns within each industry
- **Key Information**: Important metadata, descriptions, and classifications for each entry

## Directory Structure

```
industries/
├── README.md
├── data/
│   └── industries.json      # Main industry database
├── schema/
│   └── industry.schema.json # JSON Schema for validation
└── docs/
    └── CONTRIBUTING.md      # Contribution guidelines
```

## Data Structure

Each industry entry contains:
- `id`: Unique identifier
- `name`: Industry name
- `description`: Brief description of the industry
- `sector`: Primary economic sector
- `subIndustries`: Array of sub-industry entries
- `naicsCode`: Optional NAICS (North American Industry Classification System) code
- `sicCode`: Optional SIC (Standard Industrial Classification) code

## Usage

The data can be consumed as JSON and integrated with other systems. It follows standard industry classification systems while providing additional metadata for comprehensive coverage.

## Contributing

Please see [CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines on how to contribute to this database.

## License

This project is part of the InfinityXOneSystems ecosystem.