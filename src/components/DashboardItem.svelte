<script lang="ts">
  export let colSpan: string
  export let rowSpan: string
</script>

<div class="dashboard-item" style={`grid-column:${colSpan};grid-row:${rowSpan};`}>
  <slot></slot>
</div>

<style lang="scss">
  .dashboard-item {
    background: white;
    box-shadow: 0 1px 8px -2px rgba(0,0,0,0.18);
    padding: 1.62ch;
    border-radius: 0.207rem;
  }
</style>