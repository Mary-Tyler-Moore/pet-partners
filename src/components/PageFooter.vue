<template>
  <div class="text-center" style="padding-top: 5%; margin-bottom: 2.5%;">
    <div
      class="text-h6"
      :style="$q.dark.isActive ? 'color: white' : 'color: black'"
    >
      555.555.55 | petpartners@email.com
    </div>
    <div
      class="text-h6 text-italic"
      :style="$q.dark.isActive ? 'color: white' : 'color: black'"
    >
      Pet Partners | Cuddles Await
    </div>
  </div>
</template>

<script>
export default {
  name: "PageFooter"
};
</script>
