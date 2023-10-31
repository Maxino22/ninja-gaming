<script>
let title = "Ninja gaming guides"

const updateTitle = ()=>{
  title = "something else"
}
</script>

<div class="index">
  <h2>{title}</h2>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum ullam earum deserunt ipsum provident reiciendis, dolore fugiat sunt molestiae totam esse ipsa ea magnam excepturi nulla saepe id quis perferendis nobis recusandae quos assumenda error eligendi voluptatem? Dolorem, doloribus maxime optio libero provident temporibus cupiditate hic. Odit repudiandae vitae architecto!</p>
  <button on:click={updateTitle}>change title</button>
  <input type="text" bind:value={title} >
</div>


<style>
  .index {
    text-align: center;
    display: block;
    margin: 20px auto;
  }
</style>