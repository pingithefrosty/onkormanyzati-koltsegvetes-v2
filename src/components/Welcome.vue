<template>
	<section
	 class="page-section bg-primary text-white"
	 id="welcome"
	>
		<div class="container">
			<div class="container">
				<div class="row justify-content-center mb-5">
					<div class="col-lg-8 text-center">
						<h2>TISZTELT MINTAVÁROSI POLGÁROK!</h2>
						<hr class="divider light my-4">
					</div>
				</div>
				<div class="row justify-content-around mb-5">
					<div class="col-lg-5 text-justify text-white-75">
						<p>Egy önkormányzat feladatai sokrétűek, állampolgári szemmel nehezen áttekinthetőek. Mintavárosban azonban nincs takargatni valónk, ezért úgy döntöttünk, hogy a modern technika segítségével bemutatjuk Önökek településünk gazdálkodását úgy, ahogyan azt korábban csak kevesek láthatták!</p>
						<p>A XXI. század embere joggal várhatja el egy önkormányzattól, hogy az interneten is utánanézhessen, mennyit költ a település oktatásra, egészségügyre vagy épp a parkok rendben tartására. A helyi demokráciára is igaz, kettőn áll a vásár. A tisztességes településvezetés mellé tájékozott polgárok is kellenek, akik nyomon követik a döntések ésszerűségét. A közpénzek átlátható felhasználásáért küzdő K-Monitor és a Költségvetési Felelősségi Intézet szakmai segítségével létrehozott alkalmazás, amit pillanatokon belül használatba vehet, Magyarországon elsőként arra törekszik, hogy mindenki számára könnyen befogadható és értelmezhető képet adjon az önkormányzat gazdálkodásáról.</p>
					</div>
					<div class="col-lg-5 text-justify text-white-75">
						<p>A weboldal testre szabható és egyszerűen feltölthető bármely település adataival. Reméljük, Mintaváros igyekezete ragadós lesz és egyre többen teszik meg ezt az egyáltalán nem megerőltető, mégis fontos lépést az átláthatóság felé.</p>
						<p class="my-4">Kellemes böngészést kívánok,</p>
						<img
						 class="signo"
						 src="http://mintavaros.deepdata.hu/assets/img/signo.png"
						>
						<p><em>Példa Imre,<br>
								Mintaváros polgármestere</em></p>
					</div>
				</div>
				<div class="row justify-content-center mb-5">
					<div class="col-lg-8 text-center">
						<div
						 class="btn btn-outline-light btn-xl js-scroll-trigger"
						 @click="intro()"
						>Kipróbálom!</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	methods: {
		intro() {
			alert("Intro!");
		}
	}
};
</script>

<style>
.signo {
	height: 50px;
}
</style>