<template>
  <div>
   <div>
     <span class="title">
       欢迎登陆
     </span>
   </div>
   <divider>Vue Vux</divider>
   <Group>
     <XInput title="账号" v-model='acconunt'  placeholder='账号' type="text"/>
     </XInput>
     </Group>
    <x-input v-model="password" placeholder="密码" type="password" />
    <XButton type="primary" action-type="button">登陆</XButton>
     </div>
     
    </div>
</template>

<script>
import { Divider, Group, XInput, XButton } from 'vux'
export default {
  components: {
    Divider,
    Group,
    XInput,
    XButton
  },
  data () {
    return {
      acconunt: '',
      password: ''
    }
  }
}
</script>
