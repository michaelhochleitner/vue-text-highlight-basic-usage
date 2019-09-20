<template>
  <text-highlight
  	:queries="queries">{{ description }}
  </text-highlight>
</template>

<script>
module.exports = {
	data: function () {
		return {
    		queries: ['birds', 'scatt'],
    		description: 'Tropical birds scattered as Drake veered the Jeep'
  		};
	}
}
</script>