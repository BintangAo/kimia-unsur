<script lang="ts">
    import image from "../assets/image_4.png"
    import Quiz from "./ui/quiz/Quiz.svelte"
</script>

<main class="">
    <article class="flex flex-col content-center items-center  p-12 gap-6">
        <h1 class="text-xl sm:text-4xl font-medium">Sifat-Sifat Gas Mulia</h1>
        <p class="text-md sm:text-2xl text-justify">Unsur gas mulia merupakan gas yang monoatomik, tidak berwarna, tidak berasa, tidak berbau, dan sedikit larut di dalam air (kecuali helium dan neon yang tidak dapat larut dalam air.) <br> <br>

            Unsur gas mulia dikelompokkan pada golongan VIIIA karena bervalensi elektron delapan (kecuali helium yang bervalensi dua elektron). Karena ini, gas mulia pada alam memiliki kencederungan untuk tidak menangkap atau melepas elektron (stabil), yang membuat ketidakadaan senyawa yang dari gas mulia. <br> <br>
            
            Kestabilan gas mulia juga dibantu oleh energi ionisasi yang besar (membuatnya sukar melepas elektron) dan afinitas elektron yang kecil (membuatnya kecil kecenderungan untuk menangkap elektron).</p>
        <img src={image.src} alt="Data fisis gas mulia">
        <small>Data fisis gas mulia</small>
        <Quiz question="Apa yang tidak mempengaruhi kestabilan gas mulia?" answerArr={["Tingginya energi ionisasi.","Kecilnya afinitas elektron.","Jari-jari atom yang panjang.","Elektron valensik yang sudah stabil."]} correctAnswer={"Jari-jari atom yang panjang."}/>
    </article>
</main>

