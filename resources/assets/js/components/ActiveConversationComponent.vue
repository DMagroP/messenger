<template>
    <b-row class="h-100">
        <b-col cols="8">
            <b-card footer-bg-variant="light"
                    footer-border-variant="dark"
                    title="Conversación activa"
                    class="h-100">
                <b-media  vertical-align="center" class="mb-2">
                    <b-img rounded="circle" width="48" slot="aside" blank blank-color="#ccc" alt="placeholder" />
                    <b-card>Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante
                    sollicitudin. Cras purus odio, vestibulum in vulputate at, </b-card>
                </b-media>

                <b-media right-align vertical-align="center" class="mb-2">
                    <b-img rounded="circle" width="48" slot="aside" blank blank-color="#ccc" alt="placeholder" />
                    <b-card>Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante
                    sollicitudin. </b-card>
                </b-media>
                <div slot="footer">
                    <b-form class="mb-0">
                                           <b-input-group>
                            <b-form-input 
                                type="text" class="text-center"
                                placeholder="Escribe un mensaje...">
                            </b-form-input>

                            <b-input-group-append>
                                <b-button variant="primary">Enviar</b-button>   
                            </b-input-group-append>
                        </b-input-group>
                    </b-form>
                </div>
            </b-card>
        </b-col>
        <b-col cols="4">
            <b-img rounded="circle" blank width="60" height="60" blank-color="#777" alt="img" class="m-1" />
            <p>Usuario Seleccionado</p>
            <hr>
            <b-form-checkbox>
                Desactivar notificaciones
            </b-form-checkbox>
        </b-col>
    </b-row>
</template>

<script>
    export default {

        data() {
            return {

            };
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
