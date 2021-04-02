<template>
  <div class="card shadow mt-3">
    <div class="card-body">

      <h5 class="card-title"> Add Friend </h5>
      <form class="row g-3">
        <div class="col-md-6">
          <label for="inputEmail4" class="form-label">Nama</label>
          <input type="text" class="form-control" placeholder="Masukan Nama Lengkap"  />
        </div>
        <div class="col-md-6">
          <label for="inputPassword4" class="form-label">Nomor Telepon</label>
          <input type="number" class="form-control" placeholder="Masukan Nomor Telepon" />
        </div>
        <div class="col-12">
          <label for="inputAddress" class="form-label">Alamat</label>
          <input
            type="text"
            class="form-control"
            id="inputAddress"
            placeholder="Masukan Alamat"
          />
        </div>
        <div class="col-12">
          <button type="submit" class="btn btn-primary">Add</button>
        </div>
      </form>
    </div>
  </div>
</template>  


