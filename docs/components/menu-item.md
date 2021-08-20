# Menu Item

[component-header:sl-menu-item]

Menu items provide options for the user to pick from in a menu.

```html preview
<sl-menu
  style="max-width: 200px; border: solid 1px rgb(var(--sl-panel-border-color)); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-item>Option 1</sl-menu-item>
  <sl-menu-item>Option 2</sl-menu-item>
  <sl-menu-item>Option 3</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item checked>Checked</sl-menu-item>
  <sl-menu-item disabled>Disabled</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item>
    Prefix Icon
    <sl-icon slot="prefix" name="gift"></sl-icon>
  </sl-menu-item>
  <sl-menu-item>
    Suffix Icon
    <sl-icon slot="suffix" name="heart"></sl-icon>
  </sl-menu-item>
</sl-menu>
```

### Font Sizes

Use the `size` attribute to change menu-item's font size.

```html preview
<div style="display: flex; justify-content: space-between;">
  <sl-menu
  style="max-width: 200px; border: solid 1px rgb(var(--sl-panel-border-color)); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-item size="small">Option 1</sl-menu-item>
  <sl-menu-item size="small">Option 2</sl-menu-item>
  <sl-menu-item size="small">Option 3</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item size="small" checked>Checked</sl-menu-item>
  <sl-menu-item size="small" disabled>Disabled</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item size="small">
    Prefix Icon
    <sl-icon slot="prefix" name="gift"></sl-icon>
  </sl-menu-item>
  <sl-menu-item size="small">
    Suffix Icon
    <sl-icon slot="suffix" name="heart"></sl-icon>
  </sl-menu-item>
</sl-menu>


<sl-menu
  style="max-width: 200px; border: solid 1px rgb(var(--sl-panel-border-color)); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-item size="medium">Option 1</sl-menu-item>
  <sl-menu-item size="medium">Option 2</sl-menu-item>
  <sl-menu-item size="medium">Option 3</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item size="medium" checked>Checked</sl-menu-item>
  <sl-menu-item size="medium" disabled>Disabled</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item size="medium">
    Prefix Icon
    <sl-icon slot="prefix" name="gift"></sl-icon>
  </sl-menu-item>
  <sl-menu-item size="medium">
    Suffix Icon
    <sl-icon slot="suffix" name="heart"></sl-icon>
  </sl-menu-item>
</sl-menu>


<sl-menu
  style="max-width: 200px; border: solid 1px rgb(var(--sl-panel-border-color)); border-radius: var(--sl-border-radius-medium);"
>
  <sl-menu-item size="large">Option 1</sl-menu-item>
  <sl-menu-item size="large">Option 2</sl-menu-item>
  <sl-menu-item size="large">Option 3</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item size="large" checked>Checked</sl-menu-item>
  <sl-menu-item size="large" disabled>Disabled</sl-menu-item>
  <sl-menu-divider></sl-menu-divider>
  <sl-menu-item size="large">
    Prefix Icon
    <sl-icon slot="prefix" name="gift"></sl-icon>
  </sl-menu-item>
  <sl-menu-item size="large">
    Suffix Icon
    <sl-icon slot="suffix" name="heart"></sl-icon>
  </sl-menu-item>
</sl-menu>
</div>

```

[component-metadata:sl-menu-item]
