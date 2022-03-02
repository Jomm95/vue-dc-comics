<template>
    <header>
        <div>
            <nav>

                <a href=''>
                    <img class="logo" src='../assets/img/dc-logo.png'>
                </a>

                <ul>
                    <li>
                        <a href='#'>CHARACTERS</a>
                    </li>
                    <li>
                        <a href='#'>COMICS</a>
                    </li>
                    <li>
                        <a href='#'>MOVIES</a>
                    </li>
                    <li>
                        <a href='#'>TV</a>
                    </li>
                    <li>
                        <a href='#'>GAMES</a>
                    </li>
                    <li>
                        <a href='#'>COLLECTIBLES</a>
                    </li>
                    <li>
                        <a href='#'>VIDEOS</a>
                    </li>
                    <li>
                        <a href='#'>FANS</a>
                    </li>
                    <li>
                        <a href='#'>NEWS</a>
                    </li>
                    <li>
                        <a href='#'>SHOP</a>
                    </li>
                </ul>
            </nav>

        </div>
        
    </header>
</template>
    
<script>
export default {
    name : "MyHeader",
}
</script>

<style scoped lang="scss">

@import '../assets/variables.scss';

header {
    text-align: center;
}

nav {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top:10px;
    height:90px;
}

.logo {
    width: 65px;
    height: 65px;
}

ul {
    display:flex;
    justify-content: center;
    font-size: 12px;
    list-style: none;
    margin-left: 180px;

    li {
    margin:0px 12px;
    display:inline-block;
    height:90px;
    line-height: 90px;
    border-bottom: 3px solid transparent;

      a {
        text-decoration: none;
        color:black;
        font-weight: bold;
        }
    }
}

li:hover{
    cursor: pointer;
    color:#0282f9;
    border-bottom: 4px solid $primaryColor;
}

</style>
