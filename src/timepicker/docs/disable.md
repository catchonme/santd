<text lang="cn">
#### 禁用
禁用时间选择。
</text>

```html
<template>
    <div>
        <s-timepicker defaultValue="{{defaultValue}}" disabled="{{true}}"/>
    </div>
</template>
<script>
import timepicker from 'santd/timepicker';
import moment from 'moment';

export default {
    components: {
        's-timepicker': timepicker
    },
    initData() {
        return {
            defaultValue: moment('12:08:23', 'HH:mm:ss'),
        };
    }
}
</script>
```
