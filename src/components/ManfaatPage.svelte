<script lang="ts">
    import image from "../assets/image_3.png"
    import Quiz from "./ui/quiz/Quiz.svelte"
</script>

<main>
    <article class="flex flex-col content-center items-center  p-12 gap-6">
        <h1 class="text-xl sm:text-4xl font-medium">Manfaat Gas Mulia</h1>
        <ol class="text-md sm:text-2xl">
            <li>
                1. Helium : Digunakan untuk mengisis balon udara karena sifatnya ringan dan tidak mudah terbakar, campuran gas untuk tabung oksigen penyelam, sebagai zat pendingin pada rektor nuklir, untuk membentuk atmosfer inert untuk penyepuhan logam pada pembuatan kristal silikon.
            </li> <br>
            <li>
                2. Neon : Gas neon digunakan sebagai pengisis lampu hias.
            </li> <br>
            <li>
                3. Argon : Gas argon digunakan untuk mengisi bola lampu listrik agar filamen kawat tidak terbakar, digunakan untuk atmosfer yang inert untuk mencegah oksidasi.
            </li> <br>
            <li>
                4. Kripton : Digunakan untuk mengisi lampu listrik bersama argon, digunakan untuk standar panjang satu meter dari isotop kripton-86.
            </li> <br>
            <li>
                5. Xenon : Digunakan untuk membius orang yang berdarah.
            </li> <br>
            <li>
                6. Radon : Digunakan untuk radio terapi pasien kanker.
            </li>
        </ol>
    <Quiz question="Unsur apa yang digunakan untuk keperluan membuat keadaan atmosfer inert?" answerArr={["Neon","Kripton","Helium","Xenon"]} correctAnswer="Helium"/>
    </article>
</main>