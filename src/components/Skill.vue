<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
<h1 style="font-weight: 500; color: #AC7D88;">SKILL</h1>
<hr width="600px">
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>HTML</template>
    <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">80%</div>
</div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>CSS</template>
    <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 70%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">70%</div>
</div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>FIGMA</template>
    <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 85%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">85%</div>
</div>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>BOOTSTRAP</template>
    <div class="progress">
  <div class="progress-bar" role="progressbar" style="width: 75%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">75%</div>
</div>
  </WelcomeItem>

<div class="pengalaman">
  <h1 class="pnglmn" style="font-weight: 500; color: #AC7D88;">PENGALAMAN</h1>
  <ul>
    <li>Membuat web agenda kelas menggunakan laravel</li>
    <li>Membuat halaman web wisata alam menggunakan HTML dan CSS</li>
    <li>Membuat halaman web company menggunakan Bootstrap</li>
    <li>Mendesain halaman web game menggunakan figma</li>
    <li>Mendesain halaman web food delivery menggunakan figma</li>
  </ul>
</div>
</template>

<style scoped>
.pnglmn{
  margin-top: 20px;
}

li{
  margin-top: 15px;
  font-size: 17px;
}
</style>