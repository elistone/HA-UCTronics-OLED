# Changelog
## [2025.04.10.003] - Resolving start issues
- Fixing an issue with the `run.sh` script not being found.
- Fixing an issue with `run.sh` not being happy about empty else.
- Updating `run.sh` to latest version.
- Updating `config.json`
- Adjusting `apparrmor.txt`

## [2024.09.29.003] - Update to latest HA
- Removed Python from project.
- Fixing typos
- Updated README.md

## [2021.10.19.000] - Rework/Colab
Added Python project to project.

## [2021.10.18.000] - Rework/Colab
Thanks to [DC Walter](https://github.com/dcwalter)
- Added BMPs for future modification and conversion using online utility
- Removed some unnecessary duplicate code.
- Fixed some spelling/style errors
- Modified CPU, Mem, and Disk logos BMPs so that respective logos are all left-aligned.

## [2021.10.17.00] - Rework/Colab
Thanks to [DC Walter](https://github.com/dcwalter) for adding HN Logo and other options.

## [2021.10.03.040] - Rework
### Added
- Set i2c address to 1 on ssd1306_12c.c (fp = popen("find /dev/i2c-1", "r");)

## [2021.10.03.001] - Rework
### Added
- New start.sh file so that users can changes setting for project.
