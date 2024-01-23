<script>
  import PreparationTime from "./PreparationTime.svelte";

  const data = [['Total','Approximately 10 minutes'],['Preparation','5 minutes'],['Cooking','5 minutes']]
</script>
<div class="flex flex-col items-start justify-between w-full">
  <h1 class=" font-youngSerif font-semibold text-3xl text-darkCharcoal">Simple Omelette Recipe</h1>
  <p class=" mt-10 font-Outfit w-full text-base  text-wengeBrown">  An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked 
    to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>

    <PreparationTime>
      <h3 class=" font-Outfit font-semibold text-lg text-darkRaspberry mb-4"> Preparation time</h3>
      <ul class="list-disc list-inside text-darkRaspberry flex flex-col justify-around items-start gap-y-2">
        {#each data as [s,d]}
          <li class=""> <p class=" inline-block indent-5 text-base text-wengeBrown font-Outfit"><span class=" font-semibold">{s}</span>: {d}</p> </li>          
        {/each}
      </ul>
    </PreparationTime>
</div>