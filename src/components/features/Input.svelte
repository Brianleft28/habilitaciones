<script>
  export let nombre;
  export let cols;
</script>

<div class="col-md-{cols} mb-3">
  <div class="form-floating">
    <input type="text" class="form-control" id={nombre} placeholder={nombre} />
    <label for="nombre">{nombre}</label>
  </div>
</div>
