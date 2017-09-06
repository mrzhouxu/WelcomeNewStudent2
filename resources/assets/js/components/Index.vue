<template>
    <div>
      <p style="text-align:center;">欢迎新同学</p>
      <group>
        <x-input placeholder="请输入您的身份证号码" text-align="center"></x-input>
      </group>
        <x-button type="primary" style="margin-top:2em;">primary</x-button>
      
    </div>
</template>

<script>
import { XInput, Group, XButton  } from 'vux'

export default {
  components: {
    XInput,
    XButton,
    Group,
  },
  data () {
    return {
      
    }
  },
  methods: {
    
  }
}
</script>