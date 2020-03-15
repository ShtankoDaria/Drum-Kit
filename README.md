# Drum Kit

##1 Drum kit exercise

## DOM

| tag name | attributes                  | role                                                   |
| -------- | --------------------------- | ------------------------------------------------------ |
| `<div>`  | `class="keys"`              | the division that contains all user interface elements |
| `<div>`  | `data-key="65" class="key"` | the division that contains sound for A key             |
| `<div>`  | `data-key="83" class="key`  | the division that contains sound for S key             |
| `<div>`  | `data-key="68" class="key"` | the division that contains sound for D key             |
| `<div>`  | `data-key="70" class="key"` | the division that contains sound for F key             |
| `<div>`  | `data-key="71" class="key"` | the division that contains sound for G key             |
| `<div>`  | `data-key="72" class="key"` | the division that contains sound for H key             |
| `<div>`  | `data-key="74" class="key"` | the division that contains sound for J key             |
| `<div>`  | `data-key="75" class="key"` | the division that contains sound for K key             |
| `<div>`  | `data-key="76" class="key"` | the division that contains sound for L key             |

## Styling

| class name | description                      | role                                  |
| ---------- | -------------------------------- | ------------------------------------- |
| `.key`     | sets styles for all sound blocks | make block more visible and effective |
| `.playing` | sets animations for sound blocks | add orange thick border               |
| `kbd`      | sets styles for sound letters    | make output displayed in block        |
| `.sound`   | sets style for sound description | make font correctly sized and colored |

## Listeners

| type              | attached to       | callback           |
| ----------------- | ----------------- | ------------------ |
| `"transitionend"` | `predefined keys` | `removeTransition` |

## Handlers

| syntax               | parameters | return value                   | behavior                                                                     |
| -------------------- | ---------- | ------------------------------ | ---------------------------------------------------------------------------- |
| `removeTransition()` | event      | Stopped animation              | Checked event and stopped transition                                         |
| `playSound()`        | event      | Predefined sound and animation | Check event and apply an appropriate sound and animation to the selected key |
