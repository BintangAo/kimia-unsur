<script lang="ts">
    import image from "../assets/image_1.png"
    import Quiz from "./ui/quiz/Quiz.svelte"
</script>

<main>
    <article class="flex flex-col content-center items-center  p-12 gap-6">
        <h1 class="text-xl sm:text-4xl font-medium">Pengertian dari Gas Mulia</h1>
        <p class="text-md sm:text-2xl text-justify">Gas mulia digunakan oleh ahli kimia untuk menjelaskan suatu golongan unsur tertentu yang sulit bereaksi karena kestabilannya. Golongan yang dimaksud adalah golongan VIIIA yang meliputi Helium (He), Neon (Ne), Argon (Ar), Kripton (Kr), Xenon (Xe), dan Radon (Rn).</p>
        <img src={image.src} alt="Gambar Gas Mulia" width=512/>
        <Quiz question="Unsur mana yang tidak termasuk ke dalam gas mulia?" answerArr={["Kr","Br","Ar","He"]} correctAnswer={"Br"}/>
    </article>
    
</main>