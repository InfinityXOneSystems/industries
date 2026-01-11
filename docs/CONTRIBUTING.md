# Contributing to Industries Database

Thank you for your interest in contributing to the Industries Database! This document provides guidelines for contributing to this repository.

## Overview

This repository maintains a comprehensive database of industries and sub-industries worldwide. Contributions help ensure the database remains accurate, current, and exhaustive.

## How to Contribute

### Adding New Industries or Sub-Industries

1. **Fork the Repository**: Create a fork of this repository to your own GitHub account.

2. **Edit the Data File**: Modify `data/industries.json` to add new entries.

3. **Follow the Schema**: Ensure your additions conform to the schema defined in `schema/industry.schema.json`.

4. **Submit a Pull Request**: Create a pull request with a clear description of your additions.

### Data Entry Guidelines

#### Industry Entry Structure

```json
{
  "id": "unique-identifier",
  "name": "Industry Name",
  "description": "Brief description of the industry",
  "sector": "Primary Economic Sector",
  "naicsCode": "XX",
  "subIndustries": []
}
```

#### Sub-Industry Entry Structure

```json
{
  "id": "unique-sub-identifier",
  "name": "Sub-Industry Name",
  "description": "Brief description of the sub-industry",
  "naicsCode": "XXX"
}
```

### Required Fields

- **id**: A unique, lowercase, hyphenated identifier (e.g., `healthcare`, `food-manufacturing`)
- **name**: Official or commonly accepted industry name
- **description**: Clear, concise description (1-2 sentences)
- **sector**: Must be one of the predefined sectors (see schema)

### Optional Fields

- **naicsCode**: NAICS code (2-6 digits)
- **sicCode**: SIC code (4 digits)

## Validation

Before submitting, please ensure:

1. All required fields are present
2. IDs are unique across the entire dataset
3. Descriptions are clear and professional
4. Industry classifications align with standard systems (NAICS, SIC)

## Code of Conduct

Please be respectful and constructive in all interactions. We aim to build a comprehensive, accurate resource for the global community.

## Questions?

If you have questions about contributing, please open an issue in this repository.
