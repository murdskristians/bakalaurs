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
}
.array-container {
	margin-left: 2vw;
	display: flex;
	align-items: flex-end;
	flex-direction: row;
	justify-content: center;
}

.array-bar {
	background-color: rgb(93, 206, 206);
}

.menu{
	display: flex;
	flex-direction: column;
	justify-content: space-between;
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

/* .range-input{
} */

.range-input p{
	display: inline;
}

.sub-menu .array-size{
	display: inline-block;
	padding: 0;
	min-width: 60px;
}
</style>