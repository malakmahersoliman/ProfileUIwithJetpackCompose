#  Profile UI with Jetpack Compose

A modern, responsive Android UI screen built entirely using **Jetpack Compose**. This is **Task 3** of the Android Mini Project Series and demonstrates declarative UI principles, layout modifiers, and resource management — all inspired by a **Van Gogh Starry Night** theme.

---

## 🎯 Objective

Design a profile screen that includes:

-  A circular profile picture
-  A styled user name
-  A text field for the user’s bio
- A save button

Built using Jetpack Compose — **no XML used**.

---

##  UI Components

| Component     | Purpose                            |
|---------------|-------------------------------------|
| `Image()`     | Displays profile picture            |
| `Text()`      | Shows user name                     |
| `OutlinedTextField()` | Editable bio input         |
| `Button()`    | Save action                         |

All placed inside a `Column` with `Modifier` styling for spacing, alignment, and color.

---

##  Styling & Theme

This screen uses a custom **Starry Night palette** from `colors.xml`:

| Color Name     | Hex Code   | Purpose         |
|----------------|------------|------------------|
| `deepBlue`     | `#0D1B2A`  | Background color |
| `skyBlue`      | `#415A77`  | Button tint      |
| `cloudWhite`   | `#E0E1DD`  | Text field color |
| `moonYellow`   | `#FFD60A`  | Header text      |

The screen uses:

- `Modifier.fillMaxSize()`
- `Modifier.padding()`
- `Modifier.clip(CircleShape)`
- `fontSize`, `textAlign`, `colorResource`
- `remember` and `mutableStateOf` for input state

---
## 🛠 Built With

- Kotlin
- Jetpack Compose
- Material3 Components
- Android Studio Giraffe or later
