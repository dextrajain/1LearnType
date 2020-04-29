<script>
  export let segment;
</script>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href=".">
    <img src="favicon.png" width="30" height="30" class="d-inline-block align-top" alt="">
  
  1Learn typing</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="." aria-current={segment === 'home' ? 'page' : undefined} >Home <span class="sr-only">(current)</span></a>
      </li>
     <li class="nav-item ">
        <a aria-current={segment === 'guide' ? 'page' : undefined} class="nav-link" href="guide">Guide </a>
      </li>
   
  
    </ul>
  
  </div>
</nav>
