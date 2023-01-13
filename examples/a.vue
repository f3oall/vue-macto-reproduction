<script setup lang="ts">
import type { BaseProps } from './b.vue'
// import type { BaseProps } from './b'
// import from .ts file works

interface Props extends BaseProps {
  foo: string
}
defineProps<Props>()
</script>
