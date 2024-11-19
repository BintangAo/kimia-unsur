<script lang="ts">
    const {question,answerArr,correctAnswer}:{question:string,answerArr:string[],correctAnswer:string} = $props()
    let radio = $state()
    let isRight= $state()
    let message = $state()
    const checkAnswer = ()=> {
        if(!radio){
            message = "Masukkan jawaban!"
        } else 
        if(radio===correctAnswer){
            isRight=true
            message = "Kamu menjawab jawaban yang benar!"
        }else{
            isRight=false
            message = "Kamu menjawab jawaban yang salah!"
        }
    }
</script>

<div class="bg-accent w-full rounded-md p-4 sm:p-8 flex flex-col gap-4 sm:gap-6">
    <span class="text-md sm:text-xl">{question}</span> 
    <div class="flex flex-col gap-2 sm:gap-4">
        {#each answerArr as answer}
        <label class="text-sm sm:text-lg">
            <input type="radio" name="answer" value={answer} bind:group={radio}>
            {answer}
        </label>
        {/each}
    </div>
    <button type="button" onclick={checkAnswer}>Jawab</button>
    {#if message}
        {#if isRight===true}
            <div class="bg-green-800 p-2 rounded-sm"><p>{message}</p></div>
        {:else if isRight===false}
        <div class="bg-red-800 p-2 rounded-sm"><p>{message}</p></div>
        {:else}
        <div class="bg-yellow-400 p-2 rounded-sm text-black"><p>{message}</p></div>
        {/if}
    {/if}
</div>