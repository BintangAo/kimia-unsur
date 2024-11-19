<script lang="ts">
    import image from "../assets/image_3.png"
    import Quiz from "./ui/quiz/Quiz.svelte"
</script>

<main>
    <article class="flex flex-col content-center items-center  p-12 gap-6">
        <h1 class="text-xl sm:text-4xl font-medium">Keberadaan Gas Mulia di Alam</h1>
        <p class="text-md sm:text-2xl text-justify">Unsur-unsur gas mulia memiliki jumlah yang kecil di udara. Dan gas mulia yang sering ditemukan pada udara adalah gas argon sebanyak 9360 bagian per juta atau 0,934%. Tabel jumlah gas mulia yang berada di udara: </p>
        <img src={image.src} alt="Gambar Gas Mulia" width="356"/>
        <Quiz question="Kenapa Radon tidak dapat ditemukan di alam bebas?" answerArr={["Karena Radon adalah salah satu gas mulia yang radioaktif yang akan luruh setelah beberapa saat.","Karena memiliki berat massa yang tinggi di antara semua gas mulia yang membuatnya cepat untuk hancur.","Radon memiliki jari-jari yang besar yang memudahkannya bereaksi dengan senyawa lain","Radon hanya dihasilkan dari pembentukan sintetis dari hasil tangan manusia."]} correctAnswer={"Karena Radon adalah salah satu gas mulia yang radioaktif yang akan luruh setelah beberapa saat."}/>
    </article>
</main>