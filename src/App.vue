<template>
      <div class="container pt-5">
          <b-form-input v-model="phonenumber" class="mt-5"  type="tel" placeholder="Enter your phone number">"></b-form-input>
          <div class="alert-danger" v-if="phonenumber === '' " >Please enter your phone number</div>
          <b-form-input v-model="namee" type="text" class="mt-5"  placeholder="Enter your name"></b-form-input>
          <div class="alert-danger" v-if="namee === '' " >Please enter your name</div>
          <b-form-input v-model="passport" class="mt-5"  placeholder="Enter your passport info"></b-form-input>
          <div class="alert-danger" v-if="passport === '' " >Please enter your passport info</div>
          <b-form-input v-model="pinfl" class="mt-5"  placeholder="Enter your PINFL"></b-form-input>
          <div class="alert-danger" v-if="pinfl === '' " >Please enter your PINFL</div>
          <b-form-input v-model="birthdate" class="mt-5"  type="date" placeholder="Birthdate"></b-form-input>
          <div class="alert-danger" v-if="birthdate === '' " >Please enter your Birthdate</div>
          
  <button>Submit</button>

      </div>


</template>

<script>

export default {
  name: 'App',
    data(){
      return {
          phonenumber: '',
          namee:'',
          passport:'',
          pinfl:'',
          birthdate:''
      }
    }

}
</script>

<style>

</style>
