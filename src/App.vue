<template>
  <div id="app">
    	<img alt="Vue logo" src="https://vuejs.org/images/logo.png">
	  <div id="SearchAndClock">
		<SearchBar />
		<vue-clock />
	  </div>
		<Weather />
  </div>
</template>

<script>
import VueClock from '@dangvanthanh/vue-clock';
import Weather from './components/Weather';
import SearchBar from './components/SearchBar'
import './css/main.css';

export default {
  name: 'app',
  components: {
	SearchBar,
	VueClock,
	Weather
  }
}


</script>

<style scoped>
#SearchAndClock {
	display: flex;
	flex-direction: row;
	justify-content: space-between;
	align-self: center;
	padding: 10px;
	padding-top: 40px;
	padding-bottom: 60px;
	margin: 0 auto;
	width: 100%;
	max-width: 1000px;
}

.clock{
	border: 0px;
	background: #35495e;
}
</style>