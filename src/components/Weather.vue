<template>
    <weather 
        api-key="e95a1875719bdc678401dbb17a52bdcb"
        title="Houston, TX | Weather"
        latitude="29.759463"
        longitude="-95.359617"
        language="en"
        units="us">
    </weather>
</template>
 
<script>
import VueWeatherWidget from 'vue-weather-widget';
import 'vue-weather-widget/dist/css/vue-weather-widget.css';

export default {
	name: 'Weather',
    components: {
        'weather': VueWeatherWidget
    },
}
</script> 