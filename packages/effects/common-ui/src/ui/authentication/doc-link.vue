<script setup lang="ts">
defineOptions({
  name: 'DocLink',
});
</script>

<template>
  <div class="w-full sm:mx-auto md:max-w-md">
    <div class="mt-4 flex items-center justify-between">
      <span class="border-input w-[35%] border-b dark:border-gray-600"></span>
      <span class="text-muted-foreground text-center text-xs uppercase">
        萌新必读
      </span>
      <span class="border-input w-[35%] border-b dark:border-gray-600"></span>
    </div>

    <div class="mt-4 flex w-full justify-between">
      <a
        href="https://github.com/eaopen/eap-ui-admin-vben"
        target="_blank"
        class="text-primary hover:text-primary/80 text-sm"
      >
        📦 前端仓库
      </a>
      <a
        href="https://github.com/eaopen/eap-boot"
        target="_blank"
        class="text-primary hover:text-primary/80 text-sm"
      >
        📚 后端仓库
      </a>
    </div>
  </div>
</template>
