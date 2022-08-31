<template>

  
  <section class="section">
    <section class="section is-vcentered " style="height:165px; background-size: cover; background-repeat: no-repeat; background-image: url('https://assets.hiltonstatic.com/hilton-asset-cache/image/upload/t_MODx%20-%20Masthead/t_MODx%20-%20Masthead/v1584552409/Imagery/Property%20Photography/Hilton%20International/R/RIOCCHH/HILTON_COPACABANA_PISCINA_R00.jpg');">
      <h1 class="title is-1 has-text-centered has-text-white" >Olá, Robson!</h1>
    </section>
    

  <section class= "section">
      
    <section class= "section">
    
        <b-field label="Quantos hóspedes estão na sua reserva?">
            <b-select placeholder="Selecione o número de hóspedes" expanded>
                <option>
                    
                    Somente eu
                </option>
               <option>
                    
                    2 Hóspedes
                </option>
               <option>
                    
                    3 Hóspedes
                </option>
               <option>
                    
                    4 Hóspedes
                </option>
            </b-select>
        </b-field>
      
    </section>

  <div class="columns is-vcentered is-centered has-text-centered mt-6">
    <div class="column is-5">
      <b-button tag="router-link" expanded :to="{ path: '/dados' }" type="is-primary">Próximo</b-button>

    </div>
  </div>
    

       
  </section>    
  </section>
    

</template>
