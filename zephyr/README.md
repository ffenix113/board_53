# Zephyr overlay files

These files are used to build for board_53.

They are needed because Zephyr does not support this board out of the box.

# Usage
Strongly 

1. Copy/link this files in your app source folder.
2. When creating/editing a build configuration select:
    1. `raytac_mdbt53_db_40/nrf5340/cpuapp` as `Board target`
    2. `board_53.prj` as `Extra Kconfig fragments`
    3. `board_53.overlay` as `Extra Devicetree overlays`
