---
category: Browser
---

# useFileDialog

Open file dialog with ease.

## Usage

```ts
import { useFileDialog } from '@vueuse/core'

const { files, open, reset } = useDialog()
```

```html
<template>
  <button type="button" @click="open">Choose file</button>
</template>
```
