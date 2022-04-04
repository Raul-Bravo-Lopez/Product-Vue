<template>
            <div class="flexbox">

                 <div>
                    <img class="imagenRedonda" src="../assets/images/5e949a6f64b52be230b8f1084156dcd9.jpg" alt="Palmera">
                </div>

                <div>
                    <p style="font-weight: bold; font-size: 15px; margin:5px">Palmera de cacao</p>
                    <p style="font-size: 12px; color:grey; margin:5px">Pieza 425 g</p>
                    <p id="precio" style="margin:5px">1,75 €/ud.</p>
                </div>

                <div class="roundedhr"></div>

                <div>
                    <p style="color: grey; font-size: 12px; margin:5px">En carro</p>
                </div>

                <div class="flexbox2">

                    <p id ="uds" style="font-weight: bold; font-size: 20px; margin:5px">1 uds.</p>
                    <button id="buttonRestar" style="font-size: 17px; border-color:black; border-radius: 30px; height:30px; width: 30px; padding:1px">-</button>
                    <button id="buttonSumar" style="font-size: 17px; border-color:black; background-color:yellow; border-radius: 30px; height:30px; width: 30px; padding:1px">+</button>

                </div>

            </div>
</template>


<style scoped>
.flexbox{

    display: flex;
    width: 150px;
    flex-direction: column;
    background-color: white;
    border-radius: 10px 10px;
    box-shadow: 0px 0px 3px 3px rgba(180, 180, 180, 0.678);
    padding: 5px;
    
}

.flexbox2{

        display: flex;
        flex-direction: row;
        background-color: white;
        justify-content: space-between;

}

.imagenRedonda{

        width:150px;
        height:150px;
        border-radius:10px 10px;

}


.roundedhr{

        border: 0.5px solid rgb(80, 80, 80);
    
}

</style>
