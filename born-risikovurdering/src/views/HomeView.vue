
<template>
  <main>
    <h2>QUE1 Risikovurdering</h2>
    <table>
        <QuestionRow question="Antal timer siden sidste udløsning?" placeholder="Indtast antal timer"/>
        <QuestionRow question="Har du haft feber, været syg eller været hos lægen?" placeholder="Hvornår og hvorfor?"/>
        <QuestionRow question="Er du blevet vaccineret?" placeholder="Hvilken vaccine og hvornår?"/>
        <QuestionRow question="Har du haft ubeskyttet sex med en ny seksualpartner?" placeholder="Hvornår?"/>
        <QuestionRow question="Har du haft sex med en prostitueret siden sidste donation?" placeholder="Hvornår og var det beskyttet/ubeskyttet?"/>
        <QuestionRow question="Har du været på rejse til udlandet siden sidste donation?" placeholder="Hvorhenne og hvornår var du i DK igen?"/>
        <QuestionRow question="Har du fået nye piercinger, tatoveringer eller lignende?" placeholder="Hvornår?"/>
        <QuestionRow question="Har du kønsvorter, udflåd eller sår på kønsorganerne?" placeholder="Udfyld her"/>
        <QuestionRow question="Har du taget stoffer siden sidste donation?<br>Hash, ecstasy, MDMA, LSD eller andet?" placeholder="Hvilke og hvornår?"/>
    </table>
    <p>QUE1 Risikovurdering<br>Version 2 (30.09.2024)</p>
  </main>
</template>

<script lang="ts">
import QuestionRow from '@/components/QuestionRow.vue';
    import { defineComponent } from 'vue';

    export default defineComponent({
        components: {
            QuestionRow
        }
    })


</script>