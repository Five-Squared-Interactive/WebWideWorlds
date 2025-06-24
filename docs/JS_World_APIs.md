# 📦 JavaScript World APIs

The JavaScript World API enables creators to define behaviors, events, and interactivity inside MetaWorlds. These APIs are sandboxed via WorldOS and processed by the WebVerse runtime using the Straight Four engine.

---

## 🎮 Core Event Hooks

```js
World.onEnter("zone1", () => {
  World.playSound("welcome.wav");
});

World.onClick("crate_01", () => {
  World.animate("crate_01", "open");
});
