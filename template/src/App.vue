<template>
  <div id="app">
    {{#router}}
    <router-view></router-view>
    {{else}}
    <Home></Home>
    {{/router}}
  </div>
</template>

<script>
{{#unless router}}
import Home from './pages/Home'

{{/unless}}
export default {
  name: 'App'{{#router}}{{else}},
  components: {
    Home
  }{{/router}}
}
</script>
