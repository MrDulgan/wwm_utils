# WWM Utils
A set of utilities for process WWM(Where Winds Meet) game files.

## Features
- Unpack/Pack localize map files.
  - Usage: Drag and drop onto program executable.
      - The files to unpack.
      - The directories to pack. (The result file will be created in its `merged` subdirectory.)
  - Note: Some maps have valid patch(`_diff`) file, the tool can't merge them rn, so it's better to edit the maps only has a default patch file (1KB).