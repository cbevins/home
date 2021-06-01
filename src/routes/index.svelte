<script>
  import wildfire from 'images/Wildfire.jpg'
  import TinkerCard from '../components/TinkerCard.svelte'
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<h1>@cbevins Tinker Projects</h1>

<div class='row'>
  <div class='col'>
    <TinkerCard title='Fire Forecast' img='{wildfire}'
      url='https://fire-forecast.netlify.app/'
      brief='A Fire-Weather, Fuel-Moisture, and Fire-Behavior Forecast App'
      desc='Provides a 3-day forecast of hourly weather, fuel moisture, and fire behavior for any location on the globe.'
    />
  </div>
  <div class='col'>
    <TinkerCard title='Firescope' img='{wildfire}'
      url='http://cbevins-firescope.surge.sh'
      brief='Interactive Fire Behavior Simulator'
      desc='Immediately view the effects of altering fuel, weather, and terrain parameters on expected fire behavior.'
    />
  </div>
  <div class='col'>
    <TinkerCard title='Location Services' img='{wildfire}'
      brief='Global Geographic Location Search'
      desc='Explores geo-location search APIs provided by MapQuest and others'
    />
  </div>
  <div class='col'>
    <TinkerCard title='Elevation Services' img='{wildfire}'
      brief='Global Elevation, Slope, and Aspect'
      desc='Explores elevation APIs provided by MapQuest.com, USGS.gov, and Google Maps.'
    />
  </div>
  <div class='col'>
    <TinkerCard title='Weather Services' img='{wildfire}'
      brief='Global Weather Forecast Services'
      desc='Explores weather forecast APIs provided by WeatherApi.com and Tomorrow.io'
    />
  </div>
  <div class='col'>
    <TinkerCard title='Priodic Table of Fuel Models' img='{wildfire}'
      brief='Periodic Table of Fuel Models'
      desc='A visual guide to the Burgan & SCott fuel models'
    />
  </div>
</div>

<style>
	h1 {
		text-align: center;
		font-size: 2em;
		font-weight: 200;
		margin: 0 0 0.5em 0;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>
