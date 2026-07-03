# Altium ERC SDK

A Python-based Software Development Kit for creating custom **Electrical Rule Checks (ERC)** in Altium 365.

## Overview

The Altium ERC SDK enables workspace administrators and developers to build custom validation rules for electrical designs hosted in Altium 365. With this SDK, you can:

- **Validate design rules** using Python-based custom logic against your project data
- **Access project information** including components, nets, pins, and parameters
- **Report violations** back to Altium 365 with actionable insights
- **Reuse common patterns** through a comprehensive utilities library

## Features

### Custom Rule Development
- Write Python scripts with your own validation logic
- Access to complete design model data
- Built-in utilities for common electrical checks
- Easy-to-use API for reporting violations

### Design Data Access
- Load project components with designators, descriptions, and parameters
- Query electrical nets with connection information
- Access pin-level data with net connectivity
- Retrieve and parse component parameters

### Utility Functions
- Component classification helpers (IC, resistor, capacitor, etc.)
- Net type detection (power, ground, chassis, USB)
- Parameter parsing and value inference
- Common ERC patterns pre-implemented

### Integration
- Seamless integration with Altium 365 platform
- Test runs with Console and Response output
- Direct violation reporting in design projects


## License

This SDK is provided as part of the Altium 365 platform. Usage requires a valid Custom ERC Checks license.

---

**Built for Altium 365**  
*Making custom electrical validation accessible to everyone*

