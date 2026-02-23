# C# Mini Game

A small console game built while learning C# fundamentals, extending Microsoft Learn starter code with additional player mechanics — food collection, temporary freezing, and speed boosts.

---

## Overview

This project focuses on method creation and parameter handling in C#. The game runs in the console and tracks player state across three mechanics:

| Appearance | Effect |
|------------|--------|
| `(^-^)` | Speed boost (×3) |
| `(X_X)` | Temporary freeze |
| Default | Normal movement |

---

## Key Methods

- `InitializeGame()` — Sets up initial game state
- `TerminalResized()` — Checks console window dimensions
- `ShowFood()` — Displays food elements
- `ChangePlayer()` — Updates player appearance
- `FreezePlayer()` — Implements freeze mechanic
- `Move(check, speed)` — Handles movement with optional speed and termination parameters

---

## Running the Project

Open in Visual Studio or run via the .NET CLI:

```bash
dotnet run
```

---

## Development Notes

This is a freeCodeCamp C# fundamentals course project, built with minimal AI assistance. Simple by design — intended as a first hands-on project in the language.

---

## Licence

This project is licensed under the MIT Licence. See the [LICENSE](./LICENSE) file for details.
