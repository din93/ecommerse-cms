<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-4 col-sm-6">
                <div class="card">
                    <img class="card-img-top" src="http://via.placeholder.com/300x200" alt="Card image cap">
                    <div class="card-body">
                        <h5 class="card-title">Продукт 1</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <p class="price text-danger">
                            100 USD
                        </p>
                        <a href="#" class="btn btn-primary buy" data-price="100" data-product="Продукт 1">Buy now</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
