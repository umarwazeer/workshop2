<template>
    <section class="page_404">
	<div class="container">
		<div class="row">
		<div class="col-sm-12 ">
		<div class="col-sm-10 col-sm-offset-1  text-center">
		<div class="four_zero_four_bg">
			<h1 class="text-center ">404</h1>
      <p>the page you are looking for not avaible!</p>



		</div>

		<div class="contant_box_404">
		<h3 class="h2">
Page Not Fount Try, again		</h3>
    <p>Please try, again now you are offlin</p>


		<p>the page you are looking for not avaible!</p>

		<a href="" class="link_404">Go to Home</a>
	</div>
		</div>
		</div>
		</div>
	</div>
</section>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'ErrorNotFound'
})
</script>
<style>

/*======================
    404 page
=======================*/


.page_404{ padding:0px 0; margin: 0px 0%; background:#055f6e; font-family: 'Arvo', serif;
}

.page_404  img{ width:100%}

.four_zero_four_bg{

 background-image: url(https://cdn.dribbble.com/users/285475/screenshots/2083086/dribbble_1.gif);
    height: 300px;
    background-position: center;
 }


 .four_zero_four_bg h1{
 font-size:80px;
 }

  .four_zero_four_bg h3{
			 font-size:80px;
			 }

			 .link_404{
	color: #fff!important;
    padding: 10px 20px;
    background: #39ac31;
    margin: 20px 0;
    display: inline-block;}
	.contant_box_404{ margin-top:-50px;}
</style>
