<template>
    <div class="btn-group">
      <button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
        Tambah <span class="caret"></span>
      </button>
      <ul class="dropdown-menu">
        <li>
          <router-link
            :to="{name: 'CreateTransaksiKartuKreditKeluar'}"
          >
            Gunakan Kartu Kredit
          </router-link>
        </li>
        <li>
          <router-link
          :to="{name: 'CreateTransaksiKartuKreditMasuk'}"
          >
          Bayar Kartu Kredit
          </router-link>
        </li>
      </ul>
    </div>

</template>
