<script>
	import Title from "$lib/Title.svelte"
    import "../../../styles/globals.css"


</script>

<header>
    <Title title="Ninja Gaming Guides" />
    <div class="links">
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/guides">Guides</a>
    </div>
</header>

<main>
<slot></slot>
</main>

<footer>
    <p>&Copf; 2023 Ninja Gaming Guids</p>
</footer>

<style>
    header {
      display: flex;
      justify-content: center;
    }
    main {
      max-width: 960px;
      margin: 20px auto;
    }
    footer {
      text-align: center;
    }

    .links{
      margin-left: auto ;  
    }

    a{
        margin-left: 10px;
    }
  </style>