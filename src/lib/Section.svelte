<script>
    export let item1;
    export let item2;
    export let item3;
    export let title;
    export let color;
</script>

<div class="card w-25 mb-2 " style="background-color:{color};color:white;">
    <div class="card-body mt-1 mb-2">
    <h3>{title}</h3>
    <p>{item1}</p>
    <p>{item2}</p>
    <p>{item3}</p>
</div>
</div>

<style>
    div {
   	 text-align: center;
   	 margin: 3em auto;
    }
</style>