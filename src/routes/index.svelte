<script lang="ts">
  import DashboardItem from "../components/DashboardItem.svelte";

</script>
<div class="dashboard">
  <DashboardItem colSpan={'1/4'} rowSpan={'1/4'}>Item one</DashboardItem>
  <DashboardItem colSpan={'4/7'} rowSpan={'1/3'}>Item two</DashboardItem>
  <DashboardItem colSpan={'7/10'} rowSpan={'1/3'}>Item three</DashboardItem>
  <DashboardItem colSpan={'10/13'} rowSpan={'1/2'}>Item four</DashboardItem>
  <DashboardItem colSpan={'1/4'} rowSpan={'4'}>Item one</DashboardItem>
  <DashboardItem colSpan={'4/7'} rowSpan={'3/5'}>Item two</DashboardItem>
  <DashboardItem colSpan={'7/10'} rowSpan={'3/5'}>Item three</DashboardItem>
  <DashboardItem colSpan={'10/13'} rowSpan={'2/5'}>Item four</DashboardItem>
  <DashboardItem colSpan={'1/6'} rowSpan={'5/7'}>Item one</DashboardItem>
  <DashboardItem colSpan={'6/10'} rowSpan={'5/7'}>Item two</DashboardItem>
  <DashboardItem colSpan={'10/13'} rowSpan={'5/7'}>Item three</DashboardItem>
  <DashboardItem colSpan={'1/13'} rowSpan={'7/9'}>Item four</DashboardItem>
</div>

<style lang="scss">
  .dashboard {
    background: #edeeef;
    padding: 1rem;
    display: grid;
    gap: 1rem;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: repeat(8, 1fr);
  }
</style>