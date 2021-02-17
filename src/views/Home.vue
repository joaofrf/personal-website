<template>
	<!--	<div class="centerPseudo">-->
	<!--		<div class="info">-->
	<!--			<h1 class="text-white apresentacao ml-5">Olá, sou o João.</h1>-->
	<!--			<p class="myinfo">Um programador natural das Caldas da Rainha.</p>-->
	<!--&lt;!&ndash;			<p class="myinfo">A minha área de maior interesse neste momento é web mas gosto de tudo um pouco!</p>&ndash;&gt;-->
	<!--		</div>-->
	<!--		<div class="infoPhoto">-->
	<!--			<img class="photo" src="/imgs/eu.jpg" alt="Uma foto minha">-->
	<!--		</div>-->
	<!--	</div>-->

	<div>
		<div class="d-flex justify-content-center mt-5">
			<!-- source https://stackoverflow.com/questions/45666656/bootstrap-4-responsive-utilities-visible-hidden-xs-sm-lg-not-working -->
			<!--	Computer	-->
			<div class="row d-none d-lg-flex d-xl-none d-xl-flex">
				<div class="col-xs-6 text-center text-justify text-white">
					<h1 class="display-4">Olá, sou o João.</h1>
					<p class="mt-2 h3">Um programador natural das Caldas da Rainha.</p>
				</div>
				<div class="col-xs-6 text-center ml-5">
					<img src="/imgs/eu.jpg" class="photo" alt="Uma foto minha">
				</div>
			</div>
			<!--	Mobile    -->
			<div class="row d-block d-sm-block d-md-block d-lg-none">
				<div class="col-xs-6 text-center text-white">
					<h1 class="display-4">Olá, sou o João.</h1>
					<p class="mt-2 h3">Um programador natural das Caldas da Rainha.</p>
				</div>
				<div class="col-xs-6 text-center">
					<img src="/imgs/eu.jpg" class="photo" alt="Uma foto minha">
				</div>
			</div>
		</div>
	</div>

</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
	name: 'Home',
	components: {
		// HelloWorld
	}
}
</script>

<style>

.photo {
	width: 340px;
}

</style>
