# Steelcase

Steelcase is a global leader in the office furniture and workplace design industry, providing furniture, technology, and research-based insights to help organizations create effective work environments. Steelcase offers the RoomWizard API for integrating conference room scheduling and reservation systems with enterprise calendaring platforms.

**Website:** [https://www.steelcase.com](https://www.steelcase.com)

**Tech Support:** [https://www.steelcase.com/techsupport/](https://www.steelcase.com/techsupport/)

## APIs

### RoomWizard API
Conference room scheduling and reservation management API. Manage room bookings, check availability, and synchronize reservations with Microsoft Exchange, Office 365, and Google Calendar via the RoomWizard Connector.

**Human URL:** [https://www.steelcase.com/products/scheduling-systems/roomwizard/](https://www.steelcase.com/products/scheduling-systems/roomwizard/)

#### Properties
- [Documentation](https://www.steelcase.com/techsupport/types/spec-guide/)
- [OpenAPI](openapi/steelcase-roomwizard-api-openapi.yml)

## Common Properties

- [Website](https://www.steelcase.com)
- [TechSupport](https://www.steelcase.com/techsupport/)
- [Downloads](https://www.steelcase.com/techsupport/downloads/)

## Artifacts

### Spectral Rules
- [Steelcase Rules](rules/steelcase-rules.yml)

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [Room Scheduling](capabilities/room-scheduling.yaml) | Conference room booking, availability, and management (7 tools) |

**Shared Definitions:**
- [RoomWizard API](capabilities/shared/roomwizard-api.yaml)

### JSON Schema
- [Booking Schema](json-schema/steelcase-booking-schema.json)
- [Room Schema](json-schema/steelcase-room-schema.json)

### JSON Structure
- [Booking Structure](json-structure/steelcase-booking-structure.json)
- [Room Structure](json-structure/steelcase-room-structure.json)

### JSON-LD
- [Steelcase Context](json-ld/steelcase-context.jsonld)

### Examples
- [Get Bookings](examples/steelcase-get-bookings-example.json)
- [Create Booking](examples/steelcase-create-booking-example.json)
- [Get Room Availability](examples/steelcase-get-room-availability-example.json)

### Vocabulary
- [Steelcase Vocabulary](vocabulary/steelcase-vocabulary.yml)

## RoomWizard API

The RoomWizard API uses HTTP GET and POST requests to manage conference room reservations. The API is hosted on a local network at the RoomWizard Connector server.

**Base URL:** `https://{host}:{port}/api`

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/get_bookings` | GET | Retrieve room bookings |
| `/get_availability` | GET | Check room availability |
| `/create_booking` | POST | Create a new booking |
| `/cancel_booking` | POST | Cancel a booking |
| `/get_rooms` | GET | List conference rooms |
| `/get_room` | GET | Get room details |
| `/status` | GET | Connector health status |

## Calendar Integration

- Microsoft Exchange
- Microsoft Office 365
- Google Calendar

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
