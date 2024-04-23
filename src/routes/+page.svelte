<script>
    
    import PouchDB from 'pouchdb'
const dbprueba = new PouchDB('kittens');
dbprueba.info().then(function (info) {
      console.log(info);
});




</script>
<h1 class="text-4xl font-bold underline">
    Hello world!
  </h1>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="./ssr">kit.svelte.dev</a> to read the documentation</p>
