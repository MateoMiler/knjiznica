<template>
  <q-page class="flex flex-center">
    <q-card dark bordered class="bg-grey-9 my-card">
      <q-card-section>
        <q-img src="https://www.rijeka.hr/wp-content/uploads/2023/12/Nova-knjižnica-4-901x600.jpg">
          <div class="text-h3 text-weight-bolder absolute-bottom text-center">O nama</div>
        </q-img>
      </q-card-section>
      <q-card-section class="text-h4 text-justify">
        {{ o_nama }}
      </q-card-section>
    </q-card>
  </q-page>
</template>

<script setup>
import { ref } from 'vue'

// Definiranje reaktivne varijable
const o_nama = ref('Gradska knjižnica Rijeka središnja je narodna knjižnica grada Rijeke i matična knjižnica za narodne i školske knjižnice Primorsko-goranske županije. Ona je informacijsko, obrazovno, kulturno, komunikacijsko i socijalno središte Rijeke i okolice usmjereno prema novom stvaralaštvu, održivom razvoju i kvaliteti razvoja zajednice i čitateljske kulture.')
</script>

<style scoped>
.my-card {
  width: 100%;
}
</style>