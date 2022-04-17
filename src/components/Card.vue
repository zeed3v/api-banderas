<template>
  <div class="card">
      <div class="card-body">
          <h5>{{pais.name}}</h5>
          <p class="card-text">
              <span class="badge badge-dark d-block mb-1">nativeName: {{pais.nativeName}}</span>
              <span class="badge badge-info p-3 d-block mb-1">population: {{pais.population}}</span>
              <span class="badge badge-dark d-block mb-1">capital: {{pais.capital}}</span>
              <span class="badge badge-dark d-block mb-1">region: {{pais.region}}</span>
          </p>
      </div>
  </div>
</template>

<script>
export default {
    props: ['pais']

}
</script>

