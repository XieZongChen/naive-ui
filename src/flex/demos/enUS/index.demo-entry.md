# Flex

Available since `NEXT_VERSION`.

Frankly saying, it functions similarly to `n-space`. However use `n-flex` if possible.

`n-flex` utilizes the flex layout, and note that the gap property might have compatibility issues with some older browsers.

On the other hand, `n-space` involves operations at the `VNode` level, which could lead to rendering issues in certain specific use cases.

## Demos

```demo
basic.vue
vertical.vue
from-end.vue
space-between.vue
space-around.vue
center.vue
```

## API

### Flex Props

| Name | Type | Default | Description | Version |
| --- | --- | --- | --- | --- |
| align | `string` | `undefined` | Way to align items, see [align-items](https://developer.mozilla.org/zh-CN/docs/Web/CSS/align-items). | NEXT_VERSION |
| inline | `boolean` | `false` | Whether it's display is `inline-flex`. | NEXT_VERSION |
| justify | `string` | `'start'` | Way to justify content, see [justify-content](https://developer.mozilla.org/zh-CN/docs/Web/CSS/justify-content). | NEXT_VERSION |
| size | `'small' \| 'medium' \| 'large' \| number \| [number, number]` | `'medium'` | When it's a number, it will be used as vertical and horizontal gap, or it is `[horizontalGap, verticalGap]`. | NEXT_VERSION |
| vertical | `boolean` | `false` | Whether to layout content vertically. | NEXT_VERSION |
| wrap | `boolean` | `true` | Whether to wrap content if `n-flex`'s width is exceeded. | NEXT_VERSION |

### Flex Slots

| Name    | Parameters | Description      | Version      |
| ------- | ---------- | ---------------- | ------------ |
| default | `()`       | Spacing content. | NEXT_VERSION |
