<template>
 <div class="note-container">
    <note-selectors />
  </div>
</template>

<script>
import NoteSelectors from "./NoteSelectors.vue";
export default {
  name: 'note-container',
  components: {
    NoteSelectors
  } 
};
</script>