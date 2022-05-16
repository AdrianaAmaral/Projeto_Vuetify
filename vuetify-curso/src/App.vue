<template>
<div>
  <v-app class="grey ligten-4">
    <Navbar /> 

    <v-content>
     <router-view></router-view>
    </v-content>

  </v-app>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar';

export default {
  name: 'App',
  components: { Navbar },
  data () {
    return {
      //
    }
  }
}
</script>