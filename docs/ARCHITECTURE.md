# Prototype architecture

```text
microphone
  -> fiddle~
  -> partial_tracker.js
  -> allocator.js
  -> bach.roll
```

The microphone signal is analyzed by `fiddle~`. Partial records are stabilized by `partial_tracker.js`, checked against the selected ensemble in `allocator.js`, and written to `bach.roll` in midicents.

Instrument ranges and basic playing constraints are stored in `data/instruments.json`.
