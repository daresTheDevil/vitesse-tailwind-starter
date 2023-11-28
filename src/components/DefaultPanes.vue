<script setup>
import {
  SplitterComponent as EjsSplitter,
  PanesDirective as EPanes,
  PaneDirective as Epane,
} from '@syncfusion/ej2-vue-layouts';
const data = [];
</script>

<template>
  <ejs-splitter id="default-splitter">
    <e-panes>
      <e-pane content="Left Pane" size="35%" min="20%" max="40%" />
      <e-pane content="Middle Pane" size="200px" min="20%" max="40%" />
      <e-pane content="Right Pane" size="200px" />
    </e-panes>
  </ejs-splitter>
</template>

<style>
@import '../../node_modules/@syncfusion/ej2-base/styles/tailwind.css';
@import '../../node_modules/@syncfusion/ej2-vue-layouts/styles/tailwind.css';

.e-splitter {
  @apply h-full w-full flex !important;
}
.e-pane {
  @apply flex items-center justify-center bg-gray-50;
}
body > div:nth-child(3) {
  display: none !important;
}
</style>
