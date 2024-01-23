<script>
  const items = [
    "2-3 large eggs",
    " Salt, to taste",
    "Pepper, to taste",
    " 1 tablespoon of butter or oil",
    "Optional fillings: cheese, diced vegetables, cooked meats, herbs",
  ];
</script>

<div class=" w-full flex flex-col justify-around items-start border-b border-b-lightGrey">
  <h2 class=" font-youngSerif text-2xl text-nutmeg my-2">Ingredients</h2>
  <ul class="list-disc list-inside text-darkRaspberry flex flex-col justify-around items-start gap-y-2">
    {#each items as d}
      <li class=" last:mb-5"><p class=" inline-block indent-5 text-base text-wengeBrown font-Outfit">{d}</p></li>
    {/each}
  </ul>
</div>
