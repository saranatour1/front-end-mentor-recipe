<script>
const instructionsArray = [
  ["Beat the eggs", "In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. You can add a tablespoon of water or milk for a fluffier texture."],
  
  ["Heat the pan", "Place a non-stick frying pan over medium heat and add butter or oil."],
  
  ["Cook the omelette", "Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure the eggs evenly coat the surface."],
  
  ["Add fillings (optional)", "When the eggs begin to set at the edges but are still slightly runny in the middle, sprinkle your chosen fillings over one half of the omelette."],
  
  ["Fold and serve", "As the omelette continues to cook, carefully lift one edge and fold it over the fillings. Let it cook for another minute, then slide it onto a plate."],
  
  ["Enjoy", "Serve hot, with additional salt and pepper if needed."]
];
</script>

<div class=" w-full flex flex-col justify-around items-start border-b border-b-lightGrey">
  <h2 class=" font-youngSerif text-2xl text-nutmeg my-2">Instructions</h2>
  <ul class=" list-decimal list-outside ml-3 font-bold text-darkRaspberry flex flex-col justify-around items-start gap-y-2">
    {#each instructionsArray as [k,v]}
      <li class=" last:mb-5 "><p class=" font-normal inline  text-base text-wengeBrown font-Outfit"><span class=" font-bold">{k}</span> {v}</p></li>
    {/each}
  </ul>
</div>