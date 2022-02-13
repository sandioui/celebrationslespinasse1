<template>
    <div id="section1">
        <div id="section1_text">
            <h1>
                Une ambiance de sérénité, de joie,<br>d’amour et de paix.
            </h1>
            <div>
                Je vous accompagne pour vos cérémonies de mariage et évènements marquants 
                de votre vie. Vous bénéficierez d’un service professionnel et personnalisé 
                en respectant vos besoins et croyances.
            </div>
            <div>
                <a>
                    Préparons un moment mémorable
                </a>
            </div>
        </div> 
        
        <div id="section1_pictures">
            <img src="../assets/ceremonie.jpg" >
            <img src="../assets/hands.png">

        </div>
    </div>

    <div id=section2>
        <h2>
            Mes services
        </h2>
        <div class="row">
            <img src="../assets/hands_services.png">
            <div class="row_text-container">
                <h4 class="title">
                    Célébration de mariage
                </h4>
                <div class="text">
                    En tant que célébrant, je vous accompagnerai dans cette aventure 
                    importante de votre vie pour en faire une journée mémorable et 
                    inoubliable.
                </div>
                <div>
                    <img src="../assets/right_arrow.png">
                    <a>
                        En savoir plus
                    </a>
                </div>
            </div>

        </div>
        <div class="row">
            
            <div class="row_text-container">
                <h4 class="title">
                    Gestion d’événements
                </h4>
                <div class="text">
                    Peu importe le type d’événement, que ce soit un party de bureau, 
                    un événement familial ou une fête privée, n’hésitez pas à communiquer 
                    avec moi.
                </div>
                <div>
                    <img src="../assets/right_arrow.png">
                    <a>
                        En savoir plus
                    </a>
                </div>
            </div>
            <img src="../assets/event_services.png">

        </div>
        <div class="row">
            <img src="../assets/couple_services.png">
            <div class="row_text-container">
                <h4 class="title">
                    Clé en main
                </h4>
                <div class="text">
                    L’organisation d’un événement peut être stressant, il y a beaucoup 
                    de choses à penser! Nous travaillerons de concert afin que cette 
                    journée reste gravée pour de longues années.
                </div>
                <div>
                    <img src="../assets/right_arrow.png">
                    <a>
                        En savoir plus
                    </a>
                </div>
            </div>

        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    #section1 {
        display: flex;
        justify-content: space-between;
        width: 100%;
        background-color: #F4F1F0;
        padding: 8% 4% 1% 4%;
    }
    
    #section1 #section1_text {
        width: 30%;
    }

</style>