# Vue
Vue.js (pronounced /vjuː/, like view) is a library for building interactive web interfaces. The goal of Vue.js is to provide the benefits of reactive data binding and composable view components with an API that is as simple as possible.

Vue.js itself is not a full-blown framework - it is focused on the view layer only. It is therefore very easy to pick up and to integrate with other libraries or existing projects. On the other hand, when used in combination with proper tooling and supporting libraries, Vue.js is also perfectly capable of powering sophisticated Single-Page Applications.

## Reactive Data Binding
![Vue Model](https://v1.vuejs.org/images/mvvm.png)
For the simplest possible example:
```
<div id="example-1">
  Hello {{ name }}!
</div>
```
```
// this is our Model
var exampleData = {
  name: 'Vue.js'
}
// create a Vue instance, or, a "ViewModel"
// which links the View and the Model
var exampleVM = new Vue({
  el: '#example-1',
  data: exampleData
})
```
Result
```
Hello Vue.js
```