# RadiusKit

## 📌 Status

This project has been archived and is no longer actively developed.

It was created as a school project exploring a web-based management interface for a RADIUS authentication system inspired by FreeRADIUS.

## 🧠 Overview

RadiusKit is a simplified administration interface for managing RADIUS-based authentication data, including users and basic permission/group structures.

The project was motivated by the lack of a modern and user-friendly web UI for managing FreeRADIUS configurations, especially in educational environments.

The goal was to provide a lightweight alternative to traditional configuration-heavy approaches.

## ✨ Features

- User management (create, edit, delete)
- Basic password handling
- Simple group and permission assignment
- Field-based configuration for RADIUS attributes
- Minimal administrative interface for authentication data

## ⚙️ Technical Notes

Due to limited official documentation and complexity of the FreeRADIUS database schema, the implementation is intentionally simplified:

- Attribute handling is partially field-based rather than fully relational
- Only core FreeRADIUS concepts are mapped reliably
- Advanced features are not fully supported
- Data model prioritizes usability over completeness

The system is functional for basic use cases but not intended for production environments.

## 🗄️ Database Stack

- MySQL
- Drizzle ORM
- FreeRADIUS-compatible schema integration

## 📌 Disclaimer

This project is a prototype created for educational purposes.

It is not production-ready and should be used only for testing or learning scenarios.

## 📦 Notes

RadiusKit has been archived.
No further updates or feature development are planned.
