<script>
  import WelcomeCard from "../components/WelcomeCard.svelte";
</script>

<div class="home">
  <WelcomeCard />
</div>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,500;0,700;1,300;1,500;1,700&display=swap");

:global(body){
  font-family: "Poppins", sans-serif;
}

.home {
  margin: 15% 0 0;
  text-align: center;
}
</style>