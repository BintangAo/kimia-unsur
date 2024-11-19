<script lang="ts">
 let isOpen = $state(false)
</script>
<nav class="flex items-center text-2xl sm:text-4xl h-20 bg-secondary px-6 sticky top-0 ">
    <ul class="flex flex-row justify-between w-full"> 
        <li>
            <a href="/">Home</a>
        </li>
        <li>
            <button class="sm:hidden" onclick={()=>{isOpen=!isOpen}}>Link</button>
        </li>
    </ul>
    <div class={isOpen?"absolute bg-slate-900 w-screen h-screen top-0 left-0 flex flex-col pt-20 items-center":"hidden"}>
        <button class="absolute right-8 top-8" onclick={()=>{isOpen=!isOpen}}>X</button>
        <ul class="gap-4 flex flex-col">
            <li><a href="/pengertian">Pengertian Gas Mulia</a></li>
            <li><a href="/sejarah">Sejarah Gas Mulia</a></li>
            <li><a href="/keberadaan-di-alam">Keberadaan Gas Muliadi Alam</a></li>
            <li><a href="/sifat-sifat">Sifat-Sifat Gas Mulia</a></li>
            <li><a href="/senyawa">Senyawa dari Gas Mulia</a></li>
            <li><a href="/manfaat">Manfaat Gas Mulia</a></li>
        </ul>
    </div>
</nav>
<!-- svelte-ignore a11y_click_events_have_key_events -->
<!-- svelte-ignore a11y_no_static_element_interactions -->
