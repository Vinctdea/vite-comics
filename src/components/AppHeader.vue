<script>
export default{
    name: "AppHeader",
}
</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <img src="../../public/img/dc-logo.png" alt="logo dc">
            </div>
            <div class="navigation">
                <nav>
                    <a href="#">characters</a>
                   
                </nav>
            </div>
        </div>
    </header>

</template>

<style lang="scss" scoped>
header{
    height: 50px;
    padding: 1rem;

    .container{
        width: 80%;
        display: flex;
        margin: 0 auto;
        a{
            text-decoration: none;
            color: black;
            text-transform: uppercase;
        }
    }
}
    
</style>