<template>
  <p>sadsadasdasadasdasdsa</p>
</template>
<script lang="ts">
import {someLogic} from "~/logic/main"

const s = async () => {
  const r = await someLogic()
  console.log(r)
}
s()
</script>
