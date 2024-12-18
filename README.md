# Resistor-0805-Package-s-Library
# Altium Designer Project Repository

This repository contains files for an Altium Designer project, including a custom resistor library for the 0805 package. It is organized to facilitate collaborative PCB and schematic design using Git.

## Repository Contents

- **Schematic Files (.SchDoc):** Contains the circuit design schematics.
- **PCB Layout Files (.PcbDoc):** Includes the PCB layout design.
- **Custom Library (.SchLib, .PcbLib):** Includes a resistor library specifically for 0805 package components.

## Custom Resistor Library

The custom library provided in this repository supports the following:

- **Package:** 0805 (2012 Metric)
- **Resistor Values:** Common E24 and E96 series values.
- **Symbols and Footprints:** Aligned to IPC standards for footprint design.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Open the Project in Altium Designer:**
   Open the `.PrjPcb` file in Altium Designer to access the schematic and PCB layout.
3. **Use the Resistor Library:**
   - Import the `.SchLib` and `.PcbLib` files into your project.
   - Add 0805 resistors from the library to your schematic or layout as needed.

## Version Control Tips

- **Use `.gitignore`:**
  Ensure autogenerated files and backups are not tracked in Git. This repository includes a `.gitignore` file tailored for Altium Designer projects.

- **Branching:**
  Create feature branches for new designs or modifications to maintain a clean main branch.

## Contribution Guidelines

- Use descriptive commit messages.
- Test schematic and PCB changes before pushing to the repository.
- Follow Altium's best practices for design clarity and manufacturability.



---

For questions or support, please contact the repository maintainer or submit an issue.
