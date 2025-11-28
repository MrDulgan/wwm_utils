# WWM Utils
A set of utilities for process WWM(Where Winds Meet) game files.

## Features
- Unpack/Pack localize map files.
  - **Smart Unpack**: Automatically detects and merges `_diff` files (e.g., `translate_words_map_en_diff`) into the main output. (The `_diff` file must be located in the same directory.)
  - **Translation Preservation**: When unpacking, if an `entries.json` already exists, it preserves your custom translations while updating new lines from the game files.
  - **Smart Pack**: Automatically merges `_diff` entries into the main file and generates a compatible empty `_diff` file to prevent game conflicts.

## Usage
- Drag and drop onto program executable.
    - Drop map files (e.g., `translate_words_map_en`) to unpack. (Only the main file is needed; the tool will automatically find the `_diff` file if it exists in the same folder.)
    - Drop directories to pack. (The result file will be created in its `merged` subdirectory.)