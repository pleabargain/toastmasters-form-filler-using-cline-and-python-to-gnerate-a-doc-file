# System Patterns

## Architecture
- Two-file system for form processing:
  1. form_structure.json: Defines form fields and their properties
  2. form_responses.json: Stores user responses

## Technical Decisions
- JSON format chosen for:
  - Easy data structure representation
  - Simple read/write operations
  - Human-readable format
  - Maintainable structure

## Data Organization
- Personal Information section
- Membership History section
- Discovery and Attendance section
- Goals and Motivation section
- Member Promises section
- Payment Information section

## Field Types
- Text inputs
- Checkboxes
- Date fields
- Optional fields
- Multi-line text areas
