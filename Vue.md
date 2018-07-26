# Vue
<img align="right" width="300px" src="https://vuejs.org/images/logo.png">
大家好,這裡放置我Vue的學習進度及筆記

### 元件 Component

```
<script type="text/x-template" id="firstComponent">
  <tr>
      <td>{{ person.name }}</td>
      <td>{{ person.cash }}</td>
      <td>{{ person.icash }}</td>
    </tr>
</script>
```
```
Vue.component('my-component',{
  props:['person'],
  template:'#firstComponent'
});
```
```<tr is="my-component" v-for="(item, key) in data" :person="item" :key="key"></tr>```

小相簿:https://codepen.io/satanbaby/pen/OwgeXw
