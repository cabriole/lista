# Changelog

## 1.0.3

- Don't throw an `IllegalStateException` when `ListaController.submitList` is called without a RecyclerView attached.

## 1.0.2

#### Testing

- Loop main thread in `SmoothScrollToPositionAction` to avoid flakiness

## 1.0.1

#### `ListaController`

- Apply diffing by default in `submitList`
- Invalidate item decorations after adapter changes

## 1.0.0

- Initial release