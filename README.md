# Apache OpenMeetings (apache-openmeetings)
Apache OpenMeetings is a web conferencing and collaboration tool that provides video conferencing, instant messaging, white board, collaborative document editing, and other groupware tools. It offers integration APIs for LMS platforms.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-openmeetings/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-openmeetings/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Collaboration, Video Conferencing, Web Conferencing, Whiteboard, Apache, Open Source, Conferencing

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache OpenMeetings REST API
The OpenMeetings REST API provides endpoints for managing rooms, users, recordings, calendars, and file uploads, with SOAP API support for legacy integrations and plugin APIs for LMS integration (Moodle, Sakai).

**Human URL:** [https://openmeetings.apache.org/RestAPISample.html](https://openmeetings.apache.org/RestAPISample.html)

#### Tags:

 - Conferencing, REST, SOAP, Apache, Open Source

#### Properties

- [Documentation](https://openmeetings.apache.org/RestAPISample.html)
- [OpenAPI](openapi/apache-openmeetings-rest-api.json)

## Common Properties

- [GitHubOrganization](https://github.com/apache/openmeetings)
- [Documentation](https://openmeetings.apache.org/)
- [GettingStarted](https://openmeetings.apache.org/installation.html)
- [SpectralRules](rules/apache-openmeetings-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-openmeetings-vocabulary.yaml)
- [NaftikoCapability](capabilities/conferencing-workflow.yaml)
- [JSON-LD](json-ld/apache-openmeetings-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Video Conferencing | HTML5-based audio/video conferencing with multi-resolution camera support |
| Screen Sharing | Full screen sharing and recording capabilities |
| Whiteboard | Multi-instance collaborative whiteboard with document import |
| File Management | Advanced file explorer with drag-and-drop for private and public drives |
| Calendar Integration | Meeting planning with email invitations and secure hash links |
| Recording | Session recording to MP4 with audio and video capture |
| REST API | Full REST API for programmatic management of rooms, users, and recordings |
| SOAP API | Legacy SOAP API for integrations requiring XML-based communication |

## Use Cases

| Name | Description |
|------|-------------|
| LMS Integration | Integrate OpenMeetings with Moodle, Sakai, and other LMS platforms |
| Corporate Conferencing | Host virtual meetings and webinars for distributed teams |
| Remote Education | Deliver interactive online courses with whiteboard and screen sharing |
| Custom Conferencing Portal | Build branded conferencing portals using the REST API |

## Integrations

| Name | Description |
|------|-------------|
| Moodle | Official Moodle plugin for LMS integration |
| Sakai | Sakai CLE integration for academic conferencing |
| LDAP/Active Directory | Enterprise authentication via LDAP and ADS |
| OAuth2 | Social login via OAuth2 providers |
| Asterisk/VoIP | VoIP integration via Asterisk for phone conferencing |
| CalDAV | Calendar synchronization via CalDAV protocol |
| Kurento Media Server | WebRTC media server for streaming and recording |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache OpenMeetings REST API](openapi/apache-openmeetings-rest-api.json)

### JSON Schema

- [Service Result](json-schema/apache-openmeetings-service-result-schema.json)
- [Address](json-schema/apache-openmeetings-address-schema.json)
- [Appointment DTO](json-schema/apache-openmeetings-appointment-dto-schema.json)
- [Room DTO](json-schema/apache-openmeetings-room-dto-schema.json)
- [User DTO](json-schema/apache-openmeetings-user-dto-schema.json)
- [File Item DTO](json-schema/apache-openmeetings-file-item-dto-schema.json)
- [Group DTO](json-schema/apache-openmeetings-group-dto-schema.json)
- [Recording DTO](json-schema/apache-openmeetings-recording-dto-schema.json)
- [Invitation DTO](json-schema/apache-openmeetings-invitation-dto-schema.json)
- [Health](json-schema/apache-openmeetings-health-schema.json)
- [And 22 more...](json-schema/)

### JSON Structure

- [Apache OpenMeetings JSON Structures](json-structure/)

### JSON-LD

- [Apache OpenMeetings Context](json-ld/apache-openmeetings-context.jsonld)

### Examples

- [Apache OpenMeetings Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [OpenMeetings REST API](capabilities/shared/openmeetings-rest-api.yaml) — Core REST API operations for conferencing management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Conferencing Workflow](capabilities/conferencing-workflow.yaml) | OpenMeetings | 10 | Meeting Organizer, System Administrator |

## Vocabulary

- [Apache OpenMeetings Vocabulary](vocabulary/apache-openmeetings-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational and capability dimensions

## Rules

- [Apache OpenMeetings Spectral Rules](rules/apache-openmeetings-spectral-rules.yml) — 10 rules across multiple categories enforcing Apache OpenMeetings API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
