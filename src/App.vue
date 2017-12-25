<template>
    <div class="container">
        <div class="row">
            <div class="col-xs-12">
              <app-quote>
                <h2>Jocko Willinck</h2>
                <p>There is no bad team, only bad leaders.</p>
              </app-quote>
            </div>
        </div>
    </div>
</template>

<script>
    import Quote from './components/Quote.vue'

    export default {
        components: {
          appQuote: Quote,
        }
    }
</script>

<style>
</style>
