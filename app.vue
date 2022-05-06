<template>
  <div>
    <h1>{{title}}</h1>
    <h2>{{subtitle}}</h2>
    <p>{{description}}</p>
    <a v-if="email" :href="`mailto:${email}`">{{email}}</a>
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: 'Lin Zhizhao',
      subtitle: '隐藏人物睡不着',
      description: '日常互联网发现，随缘摄影分享。',
      email: 'quasimo@qq.com'
    }
  }
}
</script>