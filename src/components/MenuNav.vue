<template>
    <div>  
        <nav class="navbar navbar ">
            <ul class="nav justify-content-end">
                <li class="nav-item"><a href="#" class="nav-link active"></a>Home</li>
                <li class="nav-item"><a href="#" class="nav-link active"></a>Management</li>
                <li class="nav-item"><a href="#" class="nav-link active"></a>Services</li>
            </ul>    
        </nav> 
    </div>
</template>

<script>
export default {
     name: 'MenuNav',
     props: {

     }
}
</script>

<style scoped>
#nav{
    border-bottom: solid 1px;
}
ul li{
    padding: 0px 20px;
    padding-bottom: 5px; 
}

</style>
