<script setup>
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>My Education</template>
    SD 2011 - 2016ㅤㅤㅤ SMA 2019 - 2022 <br />
    SMP 2016 - 2019 ㅤㅤ KULIAH 2022 - SEKARANG
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Work Experience</template>
    Banyaklah Bang Pokoknya dari Jualan sampe <br />ngolek(kerja ditempat
    pengolahan sagu).
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Software Skills</template>
    HTMLㅤCSSㅤJavaScript<br />PHPㅤㅤSQL
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Interest</template>
    Suka ngoding sih walaupun ngak jago, suka denger musik, <br />fotografer,
    edit foto video, baca buku(tapi novel aja sih),<br />
    suka jadi bolang kalau dikampung dan banyak lagi.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading> Contact </template>
    E-mail : fajarmuhairi@student.uir.ac.id<br />
    Instagram : fjr.mhri<br />
    Whastapp : +6282268048433
  </WelcomeItem>
</template>
