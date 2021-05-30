<template>
	<div>
		<sorting-visualizer></sorting-visualizer>
	</div>
</template>

<script>
	import SortingVisualizer from './components/SortingVisualizer'

	export default {
		components: {
			SortingVisualizer
		}
	}
</script>
<style>
.tool {
	background-color: #EBFFF3;
	display: flex;
	font-weight: 650;
	line-height: normal;
	height: 100vh;
}
.array-container {
	margin-left: 0.5vw;
	display: flex;
	align-items: flex-end;
	flex-direction: row;
	justify-content: center;
	overflow: hidden;
}

.array-bar {
	background-color: rgb(93, 206, 206);
}

.menu-frame{
	display: flex;
	flex-direction: column;
	justify-content: space-around;
	overflow: hidden;
	background-color: #DBD4D3;
}

.sub-menu{
	display: flex;
	flex-direction: column;
	justify-content: space-around;
}

.sub-menu div{
	color: #1E2019;
	text-align: center;
	padding: 16px 16px;
}

.sub-menu div:hover,  sub-menu div:active{
	background-color: #757780;
}

.range-input{
	display: block;
}

.range-input p{
	display: block;
}

.sub-menu .array-size{
	display: block;
	padding: 0;
	min-width: 60px;
}
</style>