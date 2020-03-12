<style>

    .black-wrapper {
        background-color: rgb(27, 27, 27);
    }

    .uk-text-lead {
        max-width: 33em;
        margin: 0 auto;
        color: white;
    }

    .black-wrapper h2 {
        font-weight: 700;
        text-align: center;
        color: white;
    }

    .value-wrapper {
        margin: 0 auto;
        max-width: 50em;
    }

    .images-wrapper {
        margin: 0 auto;
        max-width: 80em;
        margin-top: 10em;
        margin-bottom: 10em;
    }

    .images-wrapper h2 {
        font-weight: 700;
        text-align: left;
        color: black;
    }

    .uk-card {
        text-align: center;
    }

    .uk-card p {
        margin-bottom: inherit;
    }

    .uk-card i {
        font-size: 64px;
    }

    .grid-fix:first-child {
        margin-left: -15px;
    }

    @media (max-width: 960px) {
        .grid-fix {
            margin-left: -15px;
        }
    }

</style>

<div class="black-wrapper uk-padding">
    <h2 class="nunito uk-margin-large-top" style="color:white;">Ne cherchez pas plus loin!</h2>
    <div class="uk-text-lead uk-margin-medium-bottom">
        Avec Immeublify, vous avez 100% de chance de trouver l'immeuble ou le client idéal.
        Rejoignez-nous pour profiter aussi des services proposés par notre équipe pour faire prospérer
        vos transactions immobilières.
    </div>

    <div class="value-wrapper uk-margin-large-bottom uk-child-width-1-3@m uk-grid-medium uk-grid-match" uk-grid>
        <div class="grid-fix" uk-scrollspy="cls:uk-animation-slide-bottom-medium">
            <div class="uk-card uk-card-default uk-padding">
                <i class="fas fa-shipping-fast"></i>
                <p>Livraison rapide</p>
            </div>
        </div>
        <div class="grid-fix" uk-scrollspy="cls:uk-animation-slide-bottom-medium">
            <div class="uk-card uk-card-default uk-padding">
                <i class="far fa-smile"></i>
                <p>Satisfait ou remboursé</p>
            </div>
        </div>
        <div class="grid-fix" k-scrollspy="cls:uk-animation-slide-bottom-medium">
            <div class="uk-card uk-card-default uk-padding">
                <i class="fas fa-dollar-sign"></i>
                <p>Promotions toute l'année</p>
            </div>
        </div>
    </div>
</div>

<div class="images-wrapper" uk-grid>
    <div class="uk-width-1-2@m uk-visible@m" uk-scrollspy="cls:uk-animation-slide-left-medium">
        <img data-src="/assets/building.svg" width="100%" alt="Immeublify" uk-img>
    </div>
    <div class="uk-width-1-2@m uk-width-1-1@s uk-padding-large uk-padding-remove-top uk-padding-remove-bottom" uk-scrollspy="cls:uk-animation-slide-bottom-medium">
        <h2 class="nunito">Y'a des gens payés pour fabriquer les immeubles.</h2>
        <div>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ligula tellus, ultricies pretium luctus at, elementum vel sapien. Fusce consectetur consectetur urna in molestie. Donec diam felis, consectetur non magna vitae, rhoncus rutrum purus. Cras egestas tellus nec massa rhoncus, ut placerat nunc hendrerit. Morbi maximus auctor massa dapibus euismod. Sed luctus vitae magna in scelerisque. Mauris ut leo sed orci molestie molestie eu at urna. Curabitur tempus justo ut semper tempus.
            Maecenas vitae lobortis nibh. Fusce et hendrerit libero. Nulla sollicitudin imperdiet justo, eu congue erat pharetra vel. Integer ornare tortor felis, a placerat dolor viverra ac. Nullam aliquam eu magna ac accumsan. Proin et elit a risus tincidunt tincidunt. Praesent varius risus quis metus iaculis porttitor. Integer id urna scelerisque, interdum tortor sit amet, lacinia elit. Aenean facilisis augue eget leo feugiat gravida. Aenean congue nulla quis rhoncus feugiat. Integer aliquet dui at tortor pulvinar, sit amet commodo metus ullamcorper.
        </div>
    </div>
</div>

<div class="images-wrapper" uk-grid>
    <div class="uk-width-1-2@m uk-width-1-1@s uk-padding-large uk-padding-remove-top uk-padding-remove-bottom" uk-scrollspy="cls:uk-animation-slide-bottom-medium">
        <h2 class="nunito">On peut même trouver ces immeubles sur Google Maps.</h2>
        <div>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ligula tellus, ultricies pretium luctus at, elementum vel sapien. Fusce consectetur consectetur urna in molestie. Donec diam felis, consectetur non magna vitae, rhoncus rutrum purus. Cras egestas tellus nec massa rhoncus, ut placerat nunc hendrerit. Morbi maximus auctor massa dapibus euismod. Sed luctus vitae magna in scelerisque. Mauris ut leo sed orci molestie molestie eu at urna. Curabitur tempus justo ut semper tempus.
        </div>
    </div>
    <div class="uk-width-1-2@m uk-visible@m" uk-scrollspy="cls:uk-animation-slide-left-medium">
        <img data-src="/assets/search_house.svg" width="100%" alt="Immeublify" uk-img>
    </div>
</div>