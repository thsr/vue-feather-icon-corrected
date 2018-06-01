# vue-feather-icon-corrected

A bug free version of vue-feather-icon

## Install

```
$ npm install --save vue-feather-icon-corrected
```


## Usage

Use it like `vue-feather-icon`, except replace with `vue-feather-icon-corrected` when importing

### global component
```javascript
// main.js
import Vue = from 'vue'
import VueFeatherIcon from 'vue-feather-icon-corrected'

Vue.use(VueFeatherIcon)
```

```vue
<tempalte>
  <feather-activity></feather-activity>
  <!-- or -->
  <feather-icon type="activity"></feather-icon>
</tempalte>
```


### local component

```vue
<script>
  import { Activity } from 'vue-feather-icon-corrected'

  export default {
    components: {
      ActivityIcon: Activity
    }
  }
</script>

<tempalte>
  <activity-icon></activity-icon>
</tempalte>
```
