<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12">
              <app-quote>
                <h2 slot="title">{{title}}</h2>
                <p slot="content">There is no bad team, only bad leaders.</p>
              </app-quote>
            </div>
        </div>
    </div>
</template>

<script>
    import Quote from './components/Quote.vue'

    export default {
        data: function(){
          return {
            title: "Jocko Willinck"
          }
        },
        components: {
          appQuote: Quote,
        }
    }
</script>

<style>
</style>
