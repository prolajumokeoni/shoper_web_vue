<template>
	<div class="table">

		<div class="left">
			<div>
				<ul>

					<li>Shopper</li>
				</ul>
				<ul class="top">
					<li>Favorites</li>
					<li>Recently</li>
				</ul>
				<ul>
					<li>Favorites</li>
					<li>Recently</li>
				</ul>
				<ul>

				</ul>
			</div>
	</div>
	<div class="right">
		
	</div>
</div>

</template>
<style scoped>
.table {
	display: flex;
}
a {
	text-decoration: none;
	color: black;
}
.left {
	width: 15%;
}
.right {
	border-right: 1px solid black;
	width: 80%;
}
li {
	list-style: none;
}
.top {
	display: flex;
	gap: 5px;
}
</style>