<script lang="ts">
    import image from "../assets/image_2.png"
    import Quiz from "./ui/quiz/Quiz.svelte"
</script>

<main class="">
    <article class="flex flex-col content-center items-center  p-12 gap-6">
        <h1 class="text-xl sm:text-4xl font-medium">Sejarah dari Gas Mulia</h1>
        <p class="text-md sm:text-2xl text-justify">Gas mulia diawali dengan penemuan oleh John Rayleigh (1842-1919) dari Inggris pada tahun 1892, yang menimbang udara yang mengandung gas nitrogen lebih berat daripada gas nitrogen yang diperoleh dari senyawa amonia (NH<small>3</small>). Rayleigh menyatakan bahwa gas Nitrogen dari udara memiliki gas yang lain yang tercampur. <br> <br>

            Pada tahun 1894, William Ramsay (1852-1916) berhasil menemukan gas yang tercampur pada penimbangan Rayleigh adalah argon dari bahasa Yunani, <i>argos</i> yaitu malas. Wiliam Ramsay kemudia menemukan gas lainnya yang termasuk pada gas mulia yaitu :
            <br><br>
            1. Pada tahun 1895, gas helium (bahasa Yunani, helios = matahari) <br>
            2. Pada tahun 1898, gas neon (neos = baru), gas kripton (kryptos = tersembunyi), dan xenon (xenos = asing). <br>
            
            <br>
            Dan pada tahun 1900, Friedrich E. Dorn berhasil menemukan gas mulia yang terakhir adalah gas radon yang dihasilkan dari peluruhan dari radium.</p>
            <img src={image.src} alt="William Ramsay" width="256">
            <small>William Ramsay</small>
            <Quiz question="Gas yang ditemukan oleh Rayleigh pada saat menimbang gas nitrogen dan membuat gas nitrogen terlihat berat adalah gas?" answerArr={["Neon","Amonia","Helium","Argon"]} correctAnswer={"Argon"}/>
    </article>
</main>

