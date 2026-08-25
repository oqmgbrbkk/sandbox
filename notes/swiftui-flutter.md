# SwiftUI / Flutter Notes

Random observations from sandbox experiments.

## SwiftUI
- Prefer `@Observable` over `@StateObject` for new code.
- Use `ToolbarItem(placement: .topBarTrailing)` for navigation bar buttons.
- `onChange` now takes a two-parameter closure: `{ oldValue, newValue in }`.

## Flutter
- `MaterialStateProperty` is now `WidgetStateProperty`.
- Use `flutter run -d chrome --web-port=5210` for quick web testing.
- Keep platform-specific code under `lib/` with conditional imports.
