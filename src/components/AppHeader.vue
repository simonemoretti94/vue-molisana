<script>

export default {
    name: 'AppHeader',
}
</script>

<template>
    <header>
        <div class="logo">
            <img src="../components/img/la-molisana-logo.png" alt="">
            <nav>
                <ul class="main_menu">
                    <a href="" class="active">Home</a>
                    <a href="" class="active">Prodotti</a>
                    <a href="" class="active">Chi Siamo</a>
                    <a href="" class="active">Contatti</a>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped>
header {
    text-align: center;
    background-color: var(--mol-light);

    & .main_menu {
        list-style: none;
        display: flex;
        justify-content: center;
        margin-top: 2rem;

        & a {
            text-decoration: none;
            padding: 1rem .5rem;
            border-radius: 8px;
            color: var(--mol-dark);
            font-weight: 600;
            margin: .25rem;

        }

        & a.active {
            background-color: var(--mol-primary);
        }
    }
}
</style>