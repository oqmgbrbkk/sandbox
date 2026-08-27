# SwiftUI Layout Notes

Trying out a few layout ideas in the sandbox.

## Things I tried

- `ViewThatFits` for a card that collapses on small screens
- Custom `Layout` for a simple staggered stack
- `matchedGeometryEffect` to transition between list and grid

## Observations

- `Layout` is powerful but easy to overcomplicate; start with `HStack`/`VStack` if possible.
- `ViewThatFits` needs a sensible fallback, not just a smaller version.
- `matchedGeometryEffect` works best when only one source view changes at a time.

## Next time

- Try `scrollTransition` for subtle parallax.
- Prototype a bottom sheet in Flutter for comparison.
