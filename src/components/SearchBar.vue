<template>
<div>
	<div id="SearchTitle">Google Search:</div>
	<form method="get" action="https://www.google.com/search">
		<div style="border-style: outset">
		<table border="0" align="center" cellpadding="0">
		<tr><td>
		<input type="text" name="q" size="25" style="color:#808080;"
		maxlength="255" value=""
		onfocus="if(this.value==this.defaultValue)this.value=''; this.style.color='black';" onblur="if(this.value=='')this.value=this.defaultValue; "/>
		<input type="submit" value="Go!" />
		</td></tr>
		</table>
		</div>
	</form>
</div>
</template>

<script>
export default {
	name: 'SearchBar',
}
</script>