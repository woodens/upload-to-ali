自定义上传文件类型

```vue
<template>
  <upload-to-ali v-model="fileUrl" accept="application/pdf" />
</template>
<script>
export default {
  data() {
    return {
      fileUrl: ''
    }
  }
}
</script>
```
