# LibreScoot

Open-source software platform for the unu Scooter Pro electric scooter

## About

LibreScoot is a microservices-based software platform designed specifically for the unu Scooter Pro electric scooter. It provides a comprehensive system for vehicle control, user interface, battery management, and over-the-air updates through Redis-based communication between specialized services.

### Key Components

- **Microservices Architecture**: Redis-based communication between 15+ specialized services
- **Hardware Integration**: Support for MDB (Middle Driver Board) and DBC (Dashboard Controller)
- **Battery Management**: NFC-based dual battery monitoring with safety controls
- **Vehicle Control**: CAN bus integration for Bosch ECU communication
- **User Interface**: Flutter-based dashboard with navigation and telemetry
- **OTA Updates**: GitHub Releases integration with Mender for safe deployment

### Hardware Platform

Designed for the unu Scooter Pro hardware architecture:
- **MDB**: Freescale i.MX6UL with SIM7100E cellular modem
- **DBC**: Display controller with NFC reader and user interface
- **Battery System**: 14s7p configuration with NFC communication
- **ECU**: Bosch motor controller with CAN bus interface

### Build System

Uses Yocto Project for embedded Linux image creation with nightly automated builds producing .mender artifacts for OTA deployment.

**Note**: This is a reverse-engineered platform based on unu Scooter Pro hardware. Experimental builds are available but not recommended for real hardware deployment.

## Links

- 🌐 [Project Website](https://librescoot.github.io)
- 📦 [Main Repository](https://github.com/librescoot/librescoot)
- 🚀 [Releases](https://github.com/librescoot/librescoot/releases)
- 📋 [Issues](https://github.com/librescoot/librescoot/issues)

## License

Licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)