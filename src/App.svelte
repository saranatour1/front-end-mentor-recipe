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

    <div class="p-10 pb-0 max-md:p-0 ">
      <img src={omeletteImage} alt="omelette sandwich" class=" rounded-lg flex items-center justify-center max-md:w-screen max-md:rounded-none " />
    </div>

    <div class=" p-10">
      <MainSection />
      <IngredientsSection />
      <Instructions />
      <Nutrients />
    </div>

  </Container>

</main>


