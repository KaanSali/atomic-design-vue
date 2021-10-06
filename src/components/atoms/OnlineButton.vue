<template>
  <button class="onlineBtn">Buy Now</button>
</template>

<script>
export default {

}
</script>

<style>
:root{
    --fg-color:black;
    --bg-color:white;
}
.onlineBtn{
    font-size: 16px;
line-height: 26px;
font-weight: 600;
text-align: center;
display: inline-block;
cursor: pointer;
background: var(--bg-color);
color: var(--fg-color);
border: 2px solid var(--fg-color);
border-radius: 0;
padding: 12px 30px;
transition: all 0.3s ease-in;
text-decoration: none;
outline: none;
}
.onlineBtn:hover{
    background: none;
color: var(--bg-color);
background-color: var(--fg-color);
}
</style>