<script>

</script>

<template>
    <div class="card">

        <section class="section">
            <label class="title">Name of file</label>
            <input class="input" name="name" />
        </section>

        <section class="section">
            <label class="title">Description</label>
            <input class="input" name="description" />
        </section>
       
      <section class="section">
        <label class="title">Upload image</label>
        <input class="input" accept="image/*" type="file" />
      </section>

      <section class="section">
         <button class="button" aria-label="submit picture & description">Submit</button>
      </section>
       
    </div>
</template>



<style scoped>
.card {
    padding: 100px;
    margin: 100px;
}

.section {
    margin: 30px;
    display: block;
}
</style>