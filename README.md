<h1>Project Documentation</h1>

[Emma Mk1 DRSSTC](https://www.mujoseph.com/projects/emma-mk1-drsstc)

<h1>File Structure</h1>

```text
Emma-Mk1-DRSSTC/
├── hardware/
│   ├── electrical/
        └── <board_name>/
            ├── assembly/                    # pick-and-place, etc.
            ├── fab/                         # gerbers, NC drill
            ├── SCHEM-<board_name>.pdf       # schematic
            └── BOM-<board_name>.xlsx        # BOM
│   ├── mechanical/
        ├── fab/
            ├──<component>/                  # .3mf, .step, .dxf, .gcode, etc.
├── firmware/
└── README.md
```
