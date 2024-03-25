<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">ISI BUKU KUNJUNGAN</h2>
        <form>
          <div class="row">
            <div class="col-md-8">
              <div class="mb-3">
                <input
                  type="text"
                  class="form-control form-control-lg rounded-5"
                  placeholder="NAMA..."
                />
              </div>
              <div class="mb-3">
                <select
                  class="form-control form-control-lg form-select round-5"
                >
                  <option value="">KATEGORI</option>
                  <option value="siswa">siswa</option>
                  <option value="Guru">Guru</option>
                  <option value="staf">Staf</option>
                  <option value="umum">Umum</option>
                </select>
              </div>
              <div class="mb-3">
                <select
                  class="form-control form-control-lg form-select rounded-5"
                >
                  <option value="">KEPERLUAN</option>
                  <option value="baca">Baca Buku</option>
                  <option value="Pinjam">Pinjam Buku</option>
                  <option value="kembalikan">kembalikan buku</option>
                </select>
              </div>
            </div>
            <div class="col-md-4">
              <img
                src="~/assets/img/img-kunjungan.png"
                alt="gambar tambah kunjungan"
              />
            </div>
          </div>
          <div class="mb-3">
            <div class="row">
              <div class="col-md-4">
                <select
                  class="form-control form-control-lg form-select rounded-5 mb-2"
                >
                  <option value="">TINGKAT</option>
                  <option value="X">X</option>
                  <option value="XI">XI</option>
                  <option value="XII">XII</option>
                </select>
              </div>
              <div class="col-md-4">
                <select
                  class="form-control form-control-lg form-select rounded-5 mb-2"
                >
                  <option value="">JURUSAN</option>
                  <option value="PPLG">PPLG</option>
                  <option value="TKJT">TKJT</option>
                  <option value="TSM">TSM</option>
                  <option value="DKV">DKV</option>
                  <option value="TOI">TOI</option>
                </select>
              </div>
              <div class="col-md-4">
                <select
                  class="form-control form control-lg form-select rounded-5 mb-2"
                >
                  <option value="">KELAS</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                </select>
              </div>
            </div>
          </div>

          <button type="submit" class="btn btn-dark btn-lg rounded-5 px-5">
            KIRIM
          </button>
        </form>
      </div>
    </div>
  </div>
</template>


<style scoped>
.form-control {
  background-color: #ace9fc !important;
  border-radius: 40px;
}
</style>