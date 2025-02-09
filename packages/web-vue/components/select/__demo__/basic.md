```yaml
title:
  zh-CN: 基本用法
  en-US: Basic Usage
```

## zh-CN

选择器的基本用法。
通过 `trigger-props` 属性自定义下拉框的属性，比如可以让下拉框自动适应最小宽度。

---

## en-US

Basic usage of selectors.
Use the `trigger-props` property to customize the properties of the drop-down box, for example, the drop-down box can automatically adapt to the minimum width.

---

```vue
<template>
  <a-space direction="vertical" size="large">
    <a-select :style="{width:'320px'}" placeholder="Please select ...">
      <a-option>Beijing</a-option>
      <a-option>Shanghai</a-option>
      <a-option>Guangzhou</a-option>
      <a-option disabled>Disabled</a-option>
    </a-select>
    <a-select defaultValue="Beijing" :style="{width:'320px'}" placeholder="Please select ..."  disabled>
      <a-option>Beijing</a-option>
      <a-option>Shanghai</a-option>
      <a-option>Guangzhou</a-option>
      <a-option disabled>Disabled</a-option>
    </a-select>
    <a-select :style="{width:'120px'}" placeholder="Select" :trigger-props="{ autoFitPopupMinWidth: true }">
      <a-option>Beijing-Beijing-Beijing</a-option>
      <a-option>Shanghai</a-option>
      <a-option>Guangzhou</a-option>
      <a-option disabled>Disabled</a-option>
    </a-select>
  </a-space>
</template>
```
