<template>
<div class="container">
  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-8">
    <div class="col">
      <front :bodyzone.sync="bodyzone"/>
    </div>
    <div class="col">
      <back :bodyzone.sync="bodyzone"/>
    </div>
  </div>
</div>
</template>

<script>
import front from './front'
import back from './back'
export default {
  name: 'bodyhuman',
  props: [],
  components: {
    front,
    back
  },
  computed: {
  },
  data () {
    return {
      bodyzone: {
      }
    }
  },
  methods: {
    closeForm () {
    }
  },
  filters: {
    fnName: function (value) {
      return value
    }
  }
}
</script>

<style>
.iq-card-body{
  flex: unset;
}
@media(max-width:557px) {
.human-back svg {
    }
}
@media(max-width:1299px) {
}
@media(max-width:479px) {

}
</style>