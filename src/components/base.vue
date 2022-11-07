<script>

    export default {
        methods: {
            signIn(){
                console.log("clicked sign in");
            }
        }
    }

</script>
<template>
    <div class="header" >
        
        <img class="logo" src="https://img.icons8.com/external-sbts2018-flat-sbts2018/58/null/external-album-photography1-sbts2018-flat-sbts2018-1.png" alt="Logo"/>
        
        <button class="sign-in" @click="signIn()">Sign In</button>
       
    </div>
</template>
<style scoped>
.header{
    width: 100%;
    display: flex;
    justify-content: space-between;
    
    /* background-color: antiquewhite; */
}
.logo {
    width: 10rem;
    height: 10rem;
}
.sign-in{

    width: 6rem;
    height: 2rem;
    border-radius: 4rem;
    font-size: 0.8rem;
    font-family: 'Helvetica Neue';
    border: none;
    background-color: aqua;
}
.sign-in:hover{
    background-color: cadetblue;
    color: #fff;
}
</style>