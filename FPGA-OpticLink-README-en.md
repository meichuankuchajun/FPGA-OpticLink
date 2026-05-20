# FPGA-OpticLink

FPGA-OpticLink is an open-source FPGA-based high-speed optical interface card project.

The goal of this project is to design and bring up a multi-channel optical interface board centered on an FPGA, while documenting the full development process in public, including architecture definition, schematic design, PCB layout, assembly, bring-up, debugging, and iterative revision.

This project is not intended to be just a demo board.  
It is designed as a real engineering-oriented platform for learning and demonstrating:

- FPGA-based board-level system design
- PCIe host interconnect
- Multi-channel optical interfaces
- High-speed serial link integration
- Power tree and clock tree design
- Hardware bring-up and debugging workflow
- Design-for-assembly and design-for-rework considerations

## Project Objectives

- Build a custom FPGA board with multi-channel optical interfaces
- Integrate PCIe host connectivity for control and/or data interaction
- Explore high-speed serial link design on a self-developed board
- Maintain a fully open development log from design to bring-up
- Create a project suitable for hardware engineering portfolio and technical discussion

## Planned Hardware Features

The exact feature set may evolve across revisions, but the current direction includes:

- FPGA-centered board architecture
- Multiple optical interface channels
- PCIe edge connector  
  - current plan: **x8 mechanical, x4 electrical**
- On-board power regulation for core, transceiver, and auxiliary rails
- Reference clock and system clock distribution
- JTAG / UART / basic debug interfaces
- Revision-friendly test points and bring-up hooks

Optional features under evaluation:

- External DDR3 memory
- Expanded host-side bandwidth in future revisions
- More advanced data path validation logic

## Development Philosophy

This project prioritizes:

1. **Engineering closure over inflated specifications**
2. **Bring-up feasibility over over-complex first revision**
3. **Open documentation over black-box progress**
4. **Iterative development over one-shot perfection**

## Repository Status

Current stage:
- Project definition and architecture planning

Next steps:
- Define revision-1 hardware scope
- Finalize module partitioning
- Decide optical channel implementation details
- Complete schematic capture
- Plan PCB layout with assembly-friendly constraints

## Development Log

Progress will be documented continuously, including:

- design decisions
- architecture trade-offs
- schematic snippets
- PCB layout notes
- assembly issues
- bring-up records
- lessons learned and revision plans

## Disclaimer

This is an actively evolving open hardware project.  
Some design choices may change between revisions as the project moves from concept to bring-up.
