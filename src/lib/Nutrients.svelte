<script>
  const data = [['Calories' ,'277kcal'],["Carbs",'0g'],['Protein','20g'],[' Fat','22g']]
</script>

<div class=" w-full flex flex-col justify-around items-start">
  <h2 class=" font-youngSerif text-2xl text-nutmeg my-2">Nutrition</h2>
  <p class="  font-Outfit w-full text-base  text-wengeBrown"> The table below shows nutritional values per serving without the additional fillings.</p>
  
  {#each data as [k,v]}
  <div class=" w-full flex items-start justify-between border-b border-b-lightGrey  font-Outfit  last:border-b-0">
    <p class=" flex-[0.5] my-3 indent-5 font-normal text-wengeBrown/65 ">{k}</p> <p class=" flex-[0.5] my-3 text-nutmeg font-bold">{v}</p>
  </div>
  {/each}


</div>