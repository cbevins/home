<script>
  import wildfire from 'images/Wildfire.jpg'
  export let brief = 'This Space Available'
  export let desc = ''
  export let img = wildfire
  export let title = 'Coming Soon'
  export let url =  ''
</script>

<div class="card mb-5 mr-5" style="width: 18rem;">
  <h4 class="card-header">
    <div class='row'>
      <div class='col-4'>
        <img src="{img}" class="card-img-top img-thumbnail rounded float-start" alt="...">
      </div>
      <div class='col'>
        {title}
      </div>
  </h4>
  <div class="card-body">
    <h5 class="card-title">{brief}</h5>
    <p class="card-text">{desc}</p>
    {#if url !== ''}
      <a href="{url}" class="btn btn-success">Check it out!</a>
    {/if}
  </div>
</div>

<style>
	img {
		width: 80%;
		max-width: 100px;
		margin: 0 0 0 0;
	}
</style>
