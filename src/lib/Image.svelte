<script>
 export let src;
 export let alt
 export let height = "100%";
 export let width = "100%";
</script>
<img {src} {alt} {height} {width}/>
<style>
  img {
      display: block;
      margin-left: auto!important;
      margin-right: auto!important;
      max-width: 300px!important;
  }
</style>
