# Grabbable 2 (Grabbable with callback)
Drag&amp;drop reorder javascript library. Pure, no css, free.

Forked from Grabbable (<https://github.com/WolfgangKurz/grabbable>), by Wolfgang Kurz.

Grabbable 2 adds the ability to bind a callback function to the drag&drop event.

## Usage

Just call grabbable() on parent node after load `grabbable.js` file.

```javascript
ParentNode.grabbable();
```

Optionally, a callback function can be added:

```javascript
ParentNode.grabbable(callbackFunction);
```

See detail usage on `sample.html`.
