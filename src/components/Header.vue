<template>
    <header>
        <div class="container">
            <img src="@/assets/images/dc-logo.png" alt="">
            <nav>
                <ul>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                    <li><a href="">ciao</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>
@import "@/assets/style/variables";
    header {
        height: 7.5rem;
        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        img {
        width: 5rem;
        height: 5rem;
        }
        nav {
            display: flex;
        }
        ul {
        list-style: none;
        display: flex;
        }
        li {
        margin: 0 20px;

        }
        a {
            color: $darkGrey;
            text-decoration: none;
        }
    }



    

    
</style>