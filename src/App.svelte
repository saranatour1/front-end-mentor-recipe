<script>
  import Container from "./lib/Container.svelte";
  import omeletteImage from './assets/image-omelette.jpeg';
  import MainSection from "./lib/MainSection.svelte";
  import IngredientsSection from "./lib/IngredientsSection.svelte";
  import Instructions from "./lib/Instructions.svelte";
  import Nutrients from "./lib/Nutrients.svelte";

</script>

<main class=" w-full h-full min-h-screen max-w-[100vw]  bg-eggshell flex flex-col justify-start items-center">
  <Container>
    <img src={omeletteImage} alt="omelette sandwich" class=" rounded-lg flex items-center justify-center" />
    <MainSection />
    <IngredientsSection />
    <Instructions />
    <Nutrients />
  </Container>

</main>


