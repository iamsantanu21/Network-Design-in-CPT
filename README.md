# Network-Design-in-CPT

Network design and simulation files built with **Cisco Packet Tracer (CPT)**. This repository is a collection of `.pkt` files — lab exercises, assignments, and exams covering network topologies, subnetting, multi-router routing, LAN design, and SNMP-based network management. Each file opens in Cisco Packet Tracer as a complete, configurable network simulation.

## Opening the files

These are **Cisco Packet Tracer** projects. You need Packet Tracer installed (free with a Cisco Networking Academy account) to open, run, and inspect them:

1. Install Cisco Packet Tracer.
2. Open any `.pkt` file (`File → Open`, or double-click).
3. Use simulation mode to trace packets, and the device CLI/config tabs to review router/switch configuration.

> `.pkt` is Packet Tracer's binary save format, so the files are not human-readable in a text editor — they must be opened in the application.

## Contents

### Network topologies
| File | Topology |
|------|----------|
| `Mesh Topology.pkt` | Mesh topology. |
| `Hybrid Topology.pkt` | Hybrid topology. |
| `tree tropology.pkt` | Tree topology *(filename misspelled "tropology")*. |
| `lan.pkt`, `lan1.pkt` | LAN designs. |

### Subnetting & routing
| File | Focus |
|------|-------|
| `subnet8.pkt`, `subnet8.1.pkt` | Subnetting exercises. |
| `Multi_router.pkt` | Multi-router network / inter-router routing. |
| `FMN.pkt` | Network design exercise. |

### SNMP (network management)
| File | Focus |
|------|-------|
| `SNMP.pkt`, `SNMP1.pkt`, `snmp2.pkt`, `SNMP final.pkt` | Successive iterations of an SNMP monitoring setup. |

### Labs, assignments & assessments
| File | Type |
|------|------|
| `Lab1.pkt`, `lab2.pkt` | Lab exercises. |
| `Assignment3.pkt` | Assignment. |
| `quiz.pkt` | Quiz. |
| `lab_exam.pkt` | Lab exam. |

## Notes

- These are coursework simulations for learning network design and configuration; they are self-contained Packet Tracer projects and require no other setup.
- Several files are versioned iterations of the same task (e.g. the `SNMP*` and `subnet8*` sets) — the "final" variants are the most complete.
- A couple of filenames contain typos or spaces (`tree tropology.pkt`, `SNMP final.pkt`); rename them if you want cleaner, script-friendly names.
