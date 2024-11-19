<script lang="ts">
    import image from "../assets/image_1.png"
    import Quiz from "./ui/quiz/Quiz.svelte"
</script>

<main>
    <article class="flex flex-col content-center items-center p-12 gap-6">
        <h1 class="text-xl sm:text-4xl font-medium">Senyawa yang Terbentuk dari Gas Mulia</h1>
        <p class="text-md sm:text-2xl text-justify">
        Walaupun di alam tidak ada senyawa dari gas mulia, pada tahun 1962 Neil Bartlett berhasil mensintetiskan senyawa xenon yang stabil yaitu XePtF<small>6</small>. Keberhasilan itu mendorong ilmuwan untuk mensintetiskan senyawa dari kripton, xenon, dan radon. Dan helium, neon dan argon sangatlah sulit bereaksi dan belum ada senyawa yang disintetiskan. <br> <br>

        Ini dapat katakan bahwa gas mulia yang dapat membuat senyawa disintetiskan memiliki kereaktifan yang besar, ini disebabkan oleh jari-jari atom. Semakin ke bawah unsur di tabel periodik, semakin tinggi jari-jari atom unsur tersebut. Yang berarti atom pada kulit terluar, elektron lebih mudah untuk ditarik oleh atom lain karena elektron memiliki daya tarik yang rendah dengan inti atom. <br> <br>

        Contoh senyawa yang dihasilkan dari campuran gas xenon dengan gas flour pada suhu 400°C pada tekanan 6 atm selama satu jam, akan menghasilkan sebuah senyawa sebagai berikut: <br> <br>

        Xe + F2 -> XeF<small>2</small> <br>
        Xe + 2F2 -> XeF<small>4</small> <br>
        Xe + 3F2 -> XeF<small>6</small> <br> <br>

        (Pada reaksi ini dipilih sebuah unsur yang memiliki keelktronegatifan yang tinggi, salah satunya unsur flour.) <br> <br>

        Senyawa ini juga bisa dihidrolisis untuk menghasilkan senyawa HF. Dengan reaksi: <br> <br>

        2XeF + 2H<small>2</small>O -> 2Xe + O<small>2</small> + 4HF <br>
        6XeF<small>4</small> + 12H<small>2</small>O -> 2XeO + 4Xe + 3O<small>2</small> + 24HF <br>
        XeF<small>6</small> + H<small>2</small>O -> XeOF<small>4</small> + 2HF <br>
        XeF<small>6</small> + 2H<small>2</small>O -> XeO<small>2</small>F<small>2</small> + 4HF <br>
        XeF<small>6</small> + 3H<small>2</small>O -> XeO<small>3</small> + 6HF <br> <br>

        Dan untuk kripton, kurang reaktif dibandingkan dengan xenon dan hanya menghasilkan senyawa KrF<small>2</small>. Dan untuk radon, senyawa yang dapat dibentuk sangatlah terbatas disebabkan oleh keradioaktifan unsur radon.
        </p>
        <Quiz question="Kenapa unsur Flour digunakan untuk membuat sebuah senyawa sintetis dengan Xenon?" answerArr={["Flour memiliki jari-jari yang rendah dibandingkan unsur Xenon.","Karena keelktronegatifan Flour yang tinggi.", "Memiliki laju reaksi yang tinggi dengan senyawa lain.","Memiliki kestabilan yang tinggi."]} correctAnswer="Karena keelktronegatifan Flour yang tinggi."/>
    </article>
</main>