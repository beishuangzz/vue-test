<template>
    <div></div>
</template>

<script lang="ts" setup>
export interface FormEmits {
    (e: 'event01', value: string): void
    (e: 'event02', value: string): void
    (e: 'event03', value: string): void
    (e: 'event04', value: string): void
    (e: 'event05', value: string): void
    (e: 'event06', value: string): void
    (e: 'event07', value: string): void
    (e: 'event08', value: string): void
    (e: 'event09', value: string): void
}

defineEmits<FormEmits>()
</script>
<style lang="less" scoped></style>
