<template>
  <div class="common-approval-page">
      <ComponentA
          ref="formRef"
          @event01="event"
      />
  </div>
</template>

<script lang="ts" setup>
import ComponentA from './components/ComponentA.vue';



const event = (a: string) => {

}
</script>
