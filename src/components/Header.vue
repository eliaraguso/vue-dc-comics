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
        </div>

                </ul>
            </nav>
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>
@import "common"
    header {
        background-color: white;
        display: flex;
        justify-content: space-between;
        img {
        width: 5rem;
        height: 5rem;
        }
        nav {
            display: flex;
            align-items: center;
        }
        ul {
        list-style: none;
        display: flex;
        }
        li {
        margin: 0 20px;

        }
    }



    

    
</style>