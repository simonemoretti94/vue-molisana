<script>

export default {
    name: 'AppFooter',
}


</script>

<template>
    <footer>
        <div class="container">
            <div class="d-flex flex-row">
                <div class="col-4">
                    <div class="logo">
                        <img src="../components/img/la-molisana-logo.png" alt="">
                    </div>
                </div>
                <div class="col-4">
                    <ul class="list-unstyled">
                        <h3 class="text-left">Pastificio</h3>
                        <li><a href="">Il Pastificio</a></li>
                        <li><a href="">Grana</a></li>
                        <li><a href="">100 anni di pasta</a></li>
                        <li><a href="">Filiera</a></li>
                        <li><a href="">Sartoria della pasta</a></li>
                    </ul>
                </div>
                <div class="col-4">
                    <ul class="list-unstyled">
                        <h3 class="text-left">Prodotti</h3>
                        <li><a href="">Le classiche</a></li>
                        <li><a href="">Le integrali</a></li>
                        <li><a href="">Le speciali</a></li>
                        <li><a href="">Le speciali</a></li>
                        <li><a href="">Le gluten-free</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style  scoped>
footer {
    min-height: 200px;
    background-color: var(--mol-light);
    background-image: url('../components/img/footer-montagne-bottom.jpg');
    background-size: cover;
    background-repeat: no-repeat;

    & .list-unstyled {
        & a {
            text-decoration: none;
            color: var(--mol-dark);
        }
    }

    & h3 {
        color: var(--mol-secondary);
        text-transform: uppercase;
    }
}
</style>