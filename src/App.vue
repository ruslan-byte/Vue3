<template>
  <div>
    Новая страница
    <br/>
    <logo-icon class="logo"/>
  </div>
</template>
<script>
import logo from "@/components/icons/logo.svg"
  export default {
  	components:
  	{
  		'logo-icon': logo
  	}
  }
</script>

<style>
.logo{width: 124px;}
</style>