<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Footer from '$lib/Footer.svelte';
    let myInfo = {
    title: "Info",
    item1: "Goh Sheng Fung",
    item2: 16,
    item3: "SMJK (C) Chung Ling",
    color:"#544179"
}
let myHobby = {
    title: "Hobby",
    item1: "Cooking",
    item2: "Guitar",
    item3: "Play badminton",
    color:"#6166B3"
}
let myPersona = {
    title: "Personality",
    item1: "Confident",
    item2: "Kind",
    item3: "Humble",
    color:"#32C1CD"
}
</script>

<Header title="My Biography" />
<Section {...myInfo}/>
<Section {...myHobby}/>
<Section {...myPersona}/>

<footer>
 <Footer gitHub="https://github.com/GSFgithub-2005"/>   
 <br>My Biography  &copy; All rights reserved.
</footer>

<style>
    footer{
        text-align: center;
        background-color: #17D7A0;
        padding: 8px;
        margin-top: 30px;
    }
</style>







