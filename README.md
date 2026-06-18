# mad-libs-story-vault
A dynamic terminal-based Mad Libs engine that utilizes placeholder parsing and local file persistence to store generated narratives.

---

# Mad-Libs-Story-Vault

A streamlined Python CLI application that transforms static templates into unique, user-driven narratives. Developed by Noelsan as part of a growing suite of optimized Python tools.

## Features

* **Dynamic Template Engine:** Uses a custom character-tracking algorithm to identify and prompt for `<placeholder>` tags within strings.
* **Automated Randomization:** Pulls from a curated dictionary of story templates to ensure variety in every session.
* **The Story Vault:** Implements file I/O handling to append and save your favorite creations with high-precision timestamps.
* **Cross-Platform Support:** Includes terminal clearing logic compatible with both Windows (`cls`) and Unix-based (`clear`) systems.

## Technical Context

This project follows the same philosophy of efficiency and "optimal" system design found in my other works:

* **LimitlessInk:** Applying secure transaction logic to freelance workflows.
* **SSP (Signal-State Pattern):** Utilizing high-performance reactive patterns for web development.
* **Survival Game Development:** Integrating resource management and emotional narrative choices.

The core logic relies on the `story_engine` function, which iterates through string characters using a boolean tracking state. This ensures that any template added to the `story_templates` dictionary is immediately compatible without needing to refactor the logic.

## How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Noelsan/mad-libs-story-vault.git
   ```
2. **Navigate to the directory:**

   ```bash
   cd mad-libs-story-vault
   ```
3. **Run the application:**

   ```bash
   python mad-libs-story-vault.py
   ```

## File Structure

* `mad-libs-story-vault.py`: The main execution script containing the engine and menu logic.
* `stories.txt`: (Auto-generated) The local database where your saved stories are stored.
