<demo>
基础用法
</demo>
<template>
<div>
    <div class="demo-desc">基础的按钮用法。</div>
    <Button>默认按钮</Button>
    <Button theme="link">链接按钮</Button>
    <Button theme="text">文字按钮</Button>
</div>
</template>

<script lang="ts">
import Button from "../lib/Button.vue";  // 这里是我的引用路径，请改为 import { Button } from 'kusa-ui'
export default {
components: {
    Button
}
}
</script>