<script>
    
    import PouchDB from 'pouchdb-browser'
const dbprueba = new PouchDB('aws');
dbprueba.info().then(function (info) {
      console.log(info);
});




</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="./">kit.svelte.dev</a> to read the documentation</p>
