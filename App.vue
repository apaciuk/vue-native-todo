<template>
<view class="container">
<Statusbar />
<Header title="ToDo App"></Header>
 </view>
</template>
<script>
import Statusbar from "./components/Statusbar";
import Header from "./components/Header";
export default {
components: {
Statusbar,
Header
}    
}
</script>
<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
</style>
