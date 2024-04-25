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
<enhanced:img src="/static/owl.jpg" sizes="min(1280px, 100vw)"/>

<div class="grid">
  {#each { length: 20 } as _, i}
  <div>{i + 1}</div>
  {/each}
  </div>
  
  <style>
  .grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 1rem;
  
  & > * {
  display: grid;
  place-content: center;
  padding: 4rem;
  font-size: 2rem;
  font-weight: 600;
  background-color: oklch(28% 0.02 270);
  border-radius: 4px;
  
  }
}
  
  </style>