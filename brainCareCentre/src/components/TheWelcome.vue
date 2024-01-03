<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import { Button } from 'ant-design-vue';
//Vue.use(Button);
</script>

<template>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>如何使用</template>
    
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>软件生态</template>
    大脑康复中心是一个开源平台,平台支持
    <a href="http://localhost:5174/" target="_blank" rel="noopener">网页端</a>,
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">安卓端</a>
    与 <button>微信端</button>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>社区文档</template>

    需要帮助?请访问我们的
    <a href="https://github.com/sanfransical/BrainCareCentre/" target="_blank" rel="noopener">主页</a>,
    <a href="https://github.com/sanfransical/BrainCareCentre/issues" target="_blank" rel="noopener">社区</a>或
    <a href="https://github.com/sanfransical/BrainCareCentre/wiki" target="_blank" rel="noopener">官方文档</a>
    更多详细介绍请见<code><a href="https://github.com/sanfransical/BrainCareCentre/blob/main/README.md" target="_blank" rel="noopener">README.md</a></code>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>支持我们</template>
    支持我们的项目,让更多人收益,只需一颗star--<a href="https://github.com/sanfransical/BrainCareCentre/" target="_blank" rel="noopener">成为支持者</a>
  </WelcomeItem>
</template>
