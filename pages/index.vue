<template>
    <div>
        <section class="bg-half-170 bg-gray d-table w-100">
            <div class="container">
                <div class="row mt-5 justify-content-center">
                    <div class="col-lg-12">
                        <div class="title-heading text-center">
                            <h1 class="heading title-dark mb-3 font-weight-bold">En Uygun Sigorta Teklifleri</h1>
                            <p class="para-desc mx-auto">Tüm sigorta firmalarından gelen teklifleri anında görün, karşılaştırın ve en uygun olanı sadece 2 dakika da poliçeleştirin!</p>
                            <div class="row mt-4 pt-2">
                                <div class="col-lg-2 col-md-4 col-6 mt-4 pt-2">
                                    <div class="card explore-feature border-0 rounded text-center bg-white header-insurancies-item">
                                        <router-link to="/kasko-sigortasi" class="text-dark">
                                        <div class="card-body">
                                            <div class="icon rounded-circle shadow-md d-inline-block">
                                               <!-- <img src="~@/assets/image/car-insurance.svg" class="avatar avatar-md-sm" alt=""> -->
                                            </div>
                                                <div class="content mt-7">
                                                <span class="mb-0">
                                                    Kasko
                                                </span>
                                            </div>
                                        </div>
                                        </router-link>
                                    </div>
                                </div>
                                <div class="col-lg-2 col-md-4 col-6 mt-4 pt-2">
                                    <div class="card explore-feature border-0 rounded text-center bg-white header-insurancies-item">
                                        <router-link to="/trafik-sigortasi" class="text-dark">
                                            <div class="card-body">
                                                <div class="icon rounded-circle shadow-md d-inline-block">
                                                  <!-- <img src="~@/assets/image/two-cars-collide.svg" class="avatar avatar-md-sm" alt=""> -->
                                                </div>
                                                <div class="content mt-7">
                                                    <span class="mb-0">
                                                        Zorunlu Trafik
                                                    </span>
                                                </div>
                                            </div>
                                        </router-link>
                                    </div>
                                </div>
                                <div class="col-lg-2 col-md-4 col-6 mt-4 pt-2">
                                    <div class="card explore-feature border-0 rounded text-center bg-white header-insurancies-item">
                                        <router-link to="/tamamlayici-saglik-sigortasi" class="text-dark">
                                        <div class="card-body">
                                            <div class="icon rounded-circle shadow-md d-inline-block">
                                               <!--  <img src="~@/assets/image/healthcare.svg" class="avatar avatar-md-sm" alt=""> -->
                                            </div>
                                            <div class="content mt-4" style="line-height:18px;">
                                                <span class="mb-0">Tamamlayıcı Sağlık </span>
                                            </div>
                                        </div>
                                        </router-link>
                                    </div>
                                </div>
                                <div class="col-lg-2 col-md-4 col-6 mt-4 pt-2">
                                    <div class="card explore-feature border-0 rounded text-center bg-white header-insurancies-item">
                                        <router-link to="/ozel-saglik-sigortasi" class="text-dark">
                                        <div class="card-body">
                                            <div class="icon rounded-circle shadow-md d-inline-block">
                                            <!-- <img src="~@/assets/image/health-care.svg" class="avatar avatar-md-sm" alt=""> -->
                                            </div>
                                                <div class="content mt-7">
                                                 <span class="mb-0">Özel Sağlık</span>
                                            </div>
                                        </div>
                                        </router-link>
                                    </div>
                                </div>
                                <div class="col-lg-2 col-md-4 col-6 mt-4 pt-2">
                                    <div class="card explore-feature border-0 rounded text-center bg-white header-insurancies-item">
                                        <router-link to="/dask-sigortasi" class="text-dark">
                                        <div class="card-body">
                                            <div class="icon rounded-circle shadow-md d-inline-block">
                                            <!-- <img src="~@/assets/image/earthquake.svg" class="avatar avatar-md-sm" alt=""> -->
                                            </div>
                                                <div class="content mt-7">
                                               <span class="mb-0"> DASK</span>
                                            </div>
                                        </div>
                                        </router-link>
                                    </div>
                                </div>
                                <div class="col-lg-2 col-md-4 col-6 mt-4 pt-2">
                                    <div class="card explore-feature border-0 rounded text-center bg-white header-insurancies-item">
                                        <router-link to="/konut-sigortasi" class="text-dark">
                                        <div class="card-body">
                                            <div class="icon rounded-circle shadow-md d-inline-block">
                                             <!-- <img src="~@/assets/image/house-protection.svg" class="avatar avatar-md-sm" alt=""> -->
                                            </div>
                                                <div class="content mt-7">
                                                <span class="mb-0">Konut</span>
                                            </div>
                                        </div>
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>