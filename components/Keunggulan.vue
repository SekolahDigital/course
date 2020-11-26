<template>
  <div class="card-keunggulan bg-dark text-white rounded mb-4">
    <div class="p-3 pt-4">
      <img src="~/assets/check.svg" class="float-left mr-3" alt srcset />
      <p class="py-2" style="width:320px;line-height:18px">{{desc}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Keunggulan",
  props: {
    desc: String
  }
};
</script>

<style>
</style>