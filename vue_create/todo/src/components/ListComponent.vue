<template>
    <div id="list">
        <div class="wrap">
           <h1>Daily ToDo List</h1>
           <ul>
               <li></li>
               <li></li>
               <li></li>
               <li></li>
               <li></li>
               <li></li>
           </ul>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    #list {background:#fff;width:100%;padding:0 20px 30px 20px;}
    #list .wrap {width:100%;}
    #list .wrap h1 {font-size:18px;text-align:center;color:#000;}
    #list .wrap ul {width:100%;}
    #list .wrap ul li {height:40px;line-height:40px;border-bottom:1px solid #ccc;}
</style>