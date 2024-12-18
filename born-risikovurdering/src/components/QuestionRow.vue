<template>
        <tr>
            <td>{{question}}</td>
            <td><input type="text" :placeholder="placeholder"></td>
            <td><input type="checkbox"><label>NEJ</label></td>
        </tr>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    props: {
        question: {type: String, required: true},
        placeholder: {type: String, required: true},
    }
})

</script>