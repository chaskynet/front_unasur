<template>
    <div class="h-100 col-md-12">
        <div class="h-100 row">
            <div class="h-100 col-md-6 division">
                <div class="text-center titulo">
                    <span>Plaza de comidas</span>
                </div>
                
                    <router-link to="accesos_pc" class="text-decoration-none">
                        <div class="row">
                            <div class="col-md-9 accion">
                                Accesos Plaza de Comidas
                            </div>
                            <div class="col-md-3 accion text-center">
                                <img v-bind:src="[encendido_acceso_1 ? '/images/layout/Acceso2.png': '/images/layout/Acceso2.png']" alt="">
                            </div>
                        </div>
                    </router-link>
                    <router-link to="iluminacion_pc" class="text-decoration-none">
                        <div class="row">
                            <div class="col-md-9 accion">
                                Iluminación
                            </div>
                            <div class="col-md-3 accion text-center">
                                <img v-bind:src="[encendido_acceso_1 ? '/images/layout/Iluminacion2.png': '/images/layout/Iluminacion2.png']" alt="">
                            </div>
                        </div>
                    </router-link>
                    <router-link to="incendio_pc" class="text-decoration-none">
                        <div class="row">
                            <div class="col-md-9 accion">
                                Alarma incendio
                            </div>
                            <div class="col-md-3 accion text-center">
                                <img v-bind:src="[encendido_acceso_1 ? '/images/layout/Iluminacion2.png': '/images/layout/Iluminacion2.png']" alt="">
                            </div>
                        </div>
                    </router-link>
                
            </div>
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
img{
    width: 36%;
}
</style>
