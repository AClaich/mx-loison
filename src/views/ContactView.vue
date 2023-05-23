<template>
    <div class="container">
        <div class="row">
            <div class="col-12 col-lg-6"></div>
            <div class="col-12 col-lg-6">
                <h1 class="mb-5">Contact</h1>
                <div class="row">
                    <textarea class="form-control col-6" aria-label="With textarea"></textarea>
                    <button type="button" class="btn btn-primary" @click="onClick">Envoyer</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    methods: {
        onClick() {
            console.log('test')
        }
    }
}
</script>