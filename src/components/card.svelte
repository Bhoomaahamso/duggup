<script>
    export let imgSrc = 'pc.jfif'
    export let text = ''

    $: bg = `bg-[url("${imgSrc}")]`
    $: cls = `h-[136px] w-[344px] bg-[url('${imgSrc}')] bg-center bg-cover rounded-t-xl`
    $: console.log(imgSrc)

</script>

<div class="card w-[344px] h-[226px] rounded-xl">  
    <!-- <p>{JSON.stringify(bg)}</p> -->
    <!-- <p>{JSON.stringify(imgSrc)}</p> -->
    <!-- <div class="max-h-[100px] overflow-clip">
        <img src={imgSrc} class="my-[0px] h-fit" alt="" srcset="">
    </div> -->
        <!-- <div class={cls} ></div> -->
        <!-- <div class={`h-[136px] w-[344px] ${bg} bg-center bg-cover rounded-t-xl`} ></div> -->
        <!-- <div style={{backgroundImage: imgSrc}} class={`h-[136px] w-[344px] bg-center bg-cover rounded-t-xl`} ></div>  -->
        <div class={`h-[136px] w-[344px] bg-[url('${imgSrc}')] bg-center bg-cover rounded-t-xl`} ></div> 
        <!-- <div class={`h-[136px] w-[344px] bg-[url('steve.jfif')] bg-center bg-cover rounded-t-xl`} ></div> -->
        <!-- <div class={`h-[136px] w-[344px] bg-[url('pc.jfif')] bg-center bg-cover rounded-t-xl`} ></div> -->
        <!-- <div class={`h-[136px] w-[344px] bg-[url('sam.jfif')] bg-center bg-cover rounded-t-xl`} ></div> -->
        <!-- <div class={`h-[136px] w-[344px] bg-[url('map.png')] bg-center bg-cover rounded-t-xl`} ></div> -->
    <div class="content p-6 bg-[#FFFFFF] rounded-b-xl">
        <p class="text-sm line-clamp-2" >{text}</p>
    </div>
    
      
    <!-- <img src={imgSrc} alt="" srcset=""> -->
</div>

