---
projectStyle: custom.css
---

# Ease Gradient

Gradients are cool, but what if you would be able to use easing in your gradient. In this way they will be smoother and versatile. That's what Ease Gradient helps you with.

Ease Gradient is a Sass thingy which you can just install, import and use.

## Install

Install the package

```bash
npm i @sil/ease-gradient -D
yarn add @sil/ease-gradient
```

Import the package in your sass file

```scss
@import "@sil/ease-gradient";
```

## Use

A simple example

```scss
@import "@sil/ease-gradient";

.element {
  background-image: ease-gradient((red, blue),');
}
```

### Options

| Argument   | Options                                                                                                                                                                                                                                                                                                                                                                           | default     | Example          |
| ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ---------------- |
| Colors     | Any css valid color                                                                                                                                                                                                                                                                                                                                                               | `()`        | `(red, #ff00aa)` |
| Easing     | ease-in-cubic, ease-in-quad, ease-out-quad, ease-out-cubic, ease-in-out-cubic, ease-in-quart, ease-out-quart, ease-in-out-quart, ease-in-quint, ease-out-quite, ease-in-out-quint, ease-in-sine, ease-out-sine, ease-in-out-sine,ease-in-expo, ease-out-expo, ease-in-out-expo, ease-in-circ, ease-out-circ, ease-in-out-circ, ease-in-sin, ease-out-sin, ease-in-out-sin, linear | `linear`    | `ease-in-cubic`  |
| Directions | 'to top', 'to right', 'to bottom', 'to left', 'to right top', 'to right bottom', 'to left bottom', 'to left top'                                                                                                                                                                                                                                                                  | 'to bottom' | 'to right top'   |

## Example

<h4>ease-in-cubic</h4><div class='examples'><div class='ease-in-cubic-to-top' title='to top'></div><div class='ease-in-cubic-to-right' title='to right'></div><div class='ease-in-cubic-to-bottom' title='to bottom'></div><div class='ease-in-cubic-to-left' title='to left'></div><div class='ease-in-cubic-to-right-top' title='to right top'></div><div class='ease-in-cubic-to-right-bottom' title='to right bottom'></div><div class='ease-in-cubic-to-left-bottom' title='to left bottom'></div><div class='ease-in-cubic-to-left-top' title='to left top'></div></div><h4>ease-in-quad</h4><div class='examples'><div class='ease-in-quad-to-top' title='to top'></div><div class='ease-in-quad-to-right' title='to right'></div><div class='ease-in-quad-to-bottom' title='to bottom'></div><div class='ease-in-quad-to-left' title='to left'></div><div class='ease-in-quad-to-right-top' title='to right top'></div><div class='ease-in-quad-to-right-bottom' title='to right bottom'></div><div class='ease-in-quad-to-left-bottom' title='to left bottom'></div><div class='ease-in-quad-to-left-top' title='to left top'></div></div><h4>ease-out-quad</h4><div class='examples'><div class='ease-out-quad-to-top' title='to top'></div><div class='ease-out-quad-to-right' title='to right'></div><div class='ease-out-quad-to-bottom' title='to bottom'></div><div class='ease-out-quad-to-left' title='to left'></div><div class='ease-out-quad-to-right-top' title='to right top'></div><div class='ease-out-quad-to-right-bottom' title='to right bottom'></div><div class='ease-out-quad-to-left-bottom' title='to left bottom'></div><div class='ease-out-quad-to-left-top' title='to left top'></div></div><h4>ease-out-cubic</h4><div class='examples'><div class='ease-out-cubic-to-top' title='to top'></div><div class='ease-out-cubic-to-right' title='to right'></div><div class='ease-out-cubic-to-bottom' title='to bottom'></div><div class='ease-out-cubic-to-left' title='to left'></div><div class='ease-out-cubic-to-right-top' title='to right top'></div><div class='ease-out-cubic-to-right-bottom' title='to right bottom'></div><div class='ease-out-cubic-to-left-bottom' title='to left bottom'></div><div class='ease-out-cubic-to-left-top' title='to left top'></div></div><h4>ease-in-out-cubic</h4><div class='examples'><div class='ease-in-out-cubic-to-top' title='to top'></div><div class='ease-in-out-cubic-to-right' title='to right'></div><div class='ease-in-out-cubic-to-bottom' title='to bottom'></div><div class='ease-in-out-cubic-to-left' title='to left'></div><div class='ease-in-out-cubic-to-right-top' title='to right top'></div><div class='ease-in-out-cubic-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-cubic-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-cubic-to-left-top' title='to left top'></div></div><h4>ease-in-quart</h4><div class='examples'><div class='ease-in-quart-to-top' title='to top'></div><div class='ease-in-quart-to-right' title='to right'></div><div class='ease-in-quart-to-bottom' title='to bottom'></div><div class='ease-in-quart-to-left' title='to left'></div><div class='ease-in-quart-to-right-top' title='to right top'></div><div class='ease-in-quart-to-right-bottom' title='to right bottom'></div><div class='ease-in-quart-to-left-bottom' title='to left bottom'></div><div class='ease-in-quart-to-left-top' title='to left top'></div></div><h4>ease-out-quart</h4><div class='examples'><div class='ease-out-quart-to-top' title='to top'></div><div class='ease-out-quart-to-right' title='to right'></div><div class='ease-out-quart-to-bottom' title='to bottom'></div><div class='ease-out-quart-to-left' title='to left'></div><div class='ease-out-quart-to-right-top' title='to right top'></div><div class='ease-out-quart-to-right-bottom' title='to right bottom'></div><div class='ease-out-quart-to-left-bottom' title='to left bottom'></div><div class='ease-out-quart-to-left-top' title='to left top'></div></div><h4>ease-in-out-quart</h4><div class='examples'><div class='ease-in-out-quart-to-top' title='to top'></div><div class='ease-in-out-quart-to-right' title='to right'></div><div class='ease-in-out-quart-to-bottom' title='to bottom'></div><div class='ease-in-out-quart-to-left' title='to left'></div><div class='ease-in-out-quart-to-right-top' title='to right top'></div><div class='ease-in-out-quart-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-quart-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-quart-to-left-top' title='to left top'></div></div><h4>ease-in-quint</h4><div class='examples'><div class='ease-in-quint-to-top' title='to top'></div><div class='ease-in-quint-to-right' title='to right'></div><div class='ease-in-quint-to-bottom' title='to bottom'></div><div class='ease-in-quint-to-left' title='to left'></div><div class='ease-in-quint-to-right-top' title='to right top'></div><div class='ease-in-quint-to-right-bottom' title='to right bottom'></div><div class='ease-in-quint-to-left-bottom' title='to left bottom'></div><div class='ease-in-quint-to-left-top' title='to left top'></div></div><h4>ease-out-quite</h4><div class='examples'><div class='ease-out-quite-to-top' title='to top'></div><div class='ease-out-quite-to-right' title='to right'></div><div class='ease-out-quite-to-bottom' title='to bottom'></div><div class='ease-out-quite-to-left' title='to left'></div><div class='ease-out-quite-to-right-top' title='to right top'></div><div class='ease-out-quite-to-right-bottom' title='to right bottom'></div><div class='ease-out-quite-to-left-bottom' title='to left bottom'></div><div class='ease-out-quite-to-left-top' title='to left top'></div></div><h4>ease-in-out-quint</h4><div class='examples'><div class='ease-in-out-quint-to-top' title='to top'></div><div class='ease-in-out-quint-to-right' title='to right'></div><div class='ease-in-out-quint-to-bottom' title='to bottom'></div><div class='ease-in-out-quint-to-left' title='to left'></div><div class='ease-in-out-quint-to-right-top' title='to right top'></div><div class='ease-in-out-quint-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-quint-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-quint-to-left-top' title='to left top'></div></div><h4>ease-in-sine</h4><div class='examples'><div class='ease-in-sine-to-top' title='to top'></div><div class='ease-in-sine-to-right' title='to right'></div><div class='ease-in-sine-to-bottom' title='to bottom'></div><div class='ease-in-sine-to-left' title='to left'></div><div class='ease-in-sine-to-right-top' title='to right top'></div><div class='ease-in-sine-to-right-bottom' title='to right bottom'></div><div class='ease-in-sine-to-left-bottom' title='to left bottom'></div><div class='ease-in-sine-to-left-top' title='to left top'></div></div><h4>ease-out-sine</h4><div class='examples'><div class='ease-out-sine-to-top' title='to top'></div><div class='ease-out-sine-to-right' title='to right'></div><div class='ease-out-sine-to-bottom' title='to bottom'></div><div class='ease-out-sine-to-left' title='to left'></div><div class='ease-out-sine-to-right-top' title='to right top'></div><div class='ease-out-sine-to-right-bottom' title='to right bottom'></div><div class='ease-out-sine-to-left-bottom' title='to left bottom'></div><div class='ease-out-sine-to-left-top' title='to left top'></div></div><h4>ease-in-out-sine</h4><div class='examples'><div class='ease-in-out-sine-to-top' title='to top'></div><div class='ease-in-out-sine-to-right' title='to right'></div><div class='ease-in-out-sine-to-bottom' title='to bottom'></div><div class='ease-in-out-sine-to-left' title='to left'></div><div class='ease-in-out-sine-to-right-top' title='to right top'></div><div class='ease-in-out-sine-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-sine-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-sine-to-left-top' title='to left top'></div></div><h4>ease-in-expo</h4><div class='examples'><div class='ease-in-expo-to-top' title='to top'></div><div class='ease-in-expo-to-right' title='to right'></div><div class='ease-in-expo-to-bottom' title='to bottom'></div><div class='ease-in-expo-to-left' title='to left'></div><div class='ease-in-expo-to-right-top' title='to right top'></div><div class='ease-in-expo-to-right-bottom' title='to right bottom'></div><div class='ease-in-expo-to-left-bottom' title='to left bottom'></div><div class='ease-in-expo-to-left-top' title='to left top'></div></div><h4>ease-out-expo</h4><div class='examples'><div class='ease-out-expo-to-top' title='to top'></div><div class='ease-out-expo-to-right' title='to right'></div><div class='ease-out-expo-to-bottom' title='to bottom'></div><div class='ease-out-expo-to-left' title='to left'></div><div class='ease-out-expo-to-right-top' title='to right top'></div><div class='ease-out-expo-to-right-bottom' title='to right bottom'></div><div class='ease-out-expo-to-left-bottom' title='to left bottom'></div><div class='ease-out-expo-to-left-top' title='to left top'></div></div><h4>ease-in-out-expo</h4><div class='examples'><div class='ease-in-out-expo-to-top' title='to top'></div><div class='ease-in-out-expo-to-right' title='to right'></div><div class='ease-in-out-expo-to-bottom' title='to bottom'></div><div class='ease-in-out-expo-to-left' title='to left'></div><div class='ease-in-out-expo-to-right-top' title='to right top'></div><div class='ease-in-out-expo-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-expo-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-expo-to-left-top' title='to left top'></div></div><h4>ease-in-circ</h4><div class='examples'><div class='ease-in-circ-to-top' title='to top'></div><div class='ease-in-circ-to-right' title='to right'></div><div class='ease-in-circ-to-bottom' title='to bottom'></div><div class='ease-in-circ-to-left' title='to left'></div><div class='ease-in-circ-to-right-top' title='to right top'></div><div class='ease-in-circ-to-right-bottom' title='to right bottom'></div><div class='ease-in-circ-to-left-bottom' title='to left bottom'></div><div class='ease-in-circ-to-left-top' title='to left top'></div></div><h4>ease-out-circ</h4><div class='examples'><div class='ease-out-circ-to-top' title='to top'></div><div class='ease-out-circ-to-right' title='to right'></div><div class='ease-out-circ-to-bottom' title='to bottom'></div><div class='ease-out-circ-to-left' title='to left'></div><div class='ease-out-circ-to-right-top' title='to right top'></div><div class='ease-out-circ-to-right-bottom' title='to right bottom'></div><div class='ease-out-circ-to-left-bottom' title='to left bottom'></div><div class='ease-out-circ-to-left-top' title='to left top'></div></div><h4>ease-in-out-circ</h4><div class='examples'><div class='ease-in-out-circ-to-top' title='to top'></div><div class='ease-in-out-circ-to-right' title='to right'></div><div class='ease-in-out-circ-to-bottom' title='to bottom'></div><div class='ease-in-out-circ-to-left' title='to left'></div><div class='ease-in-out-circ-to-right-top' title='to right top'></div><div class='ease-in-out-circ-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-circ-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-circ-to-left-top' title='to left top'></div></div><h4>ease-in-sin</h4><div class='examples'><div class='ease-in-sin-to-top' title='to top'></div><div class='ease-in-sin-to-right' title='to right'></div><div class='ease-in-sin-to-bottom' title='to bottom'></div><div class='ease-in-sin-to-left' title='to left'></div><div class='ease-in-sin-to-right-top' title='to right top'></div><div class='ease-in-sin-to-right-bottom' title='to right bottom'></div><div class='ease-in-sin-to-left-bottom' title='to left bottom'></div><div class='ease-in-sin-to-left-top' title='to left top'></div></div><h4>ease-out-sin</h4><div class='examples'><div class='ease-out-sin-to-top' title='to top'></div><div class='ease-out-sin-to-right' title='to right'></div><div class='ease-out-sin-to-bottom' title='to bottom'></div><div class='ease-out-sin-to-left' title='to left'></div><div class='ease-out-sin-to-right-top' title='to right top'></div><div class='ease-out-sin-to-right-bottom' title='to right bottom'></div><div class='ease-out-sin-to-left-bottom' title='to left bottom'></div><div class='ease-out-sin-to-left-top' title='to left top'></div></div><h4>ease-in-out-sin</h4><div class='examples'><div class='ease-in-out-sin-to-top' title='to top'></div><div class='ease-in-out-sin-to-right' title='to right'></div><div class='ease-in-out-sin-to-bottom' title='to bottom'></div><div class='ease-in-out-sin-to-left' title='to left'></div><div class='ease-in-out-sin-to-right-top' title='to right top'></div><div class='ease-in-out-sin-to-right-bottom' title='to right bottom'></div><div class='ease-in-out-sin-to-left-bottom' title='to left bottom'></div><div class='ease-in-out-sin-to-left-top' title='to left top'></div></div><h4>linear</h4><div class='examples'><div class='linear-to-top' title='to top'></div><div class='linear-to-right' title='to right'></div><div class='linear-to-bottom' title='to bottom'></div><div class='linear-to-left' title='to left'></div><div class='linear-to-right-top' title='to right top'></div><div class='linear-to-right-bottom' title='to right bottom'></div><div class='linear-to-left-bottom' title='to left bottom'></div><div class='linear-to-left-top' title='to left top'></div></div>
