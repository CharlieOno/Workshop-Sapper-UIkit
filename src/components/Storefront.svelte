<style>

    h1 {
        font-weight: 700;
        font-size: 2.5rem;
        line-height: 1.1;
    }

    .uk-text-lead {
        font-weight: 100;
        font-size: 1rem;
    }

    .storefront-wrapper {
        height: calc(100vh - 80px);
        margin: 0 auto;
        max-width: 80em;
    }

    .storefront-wrapper .cell {
        position: relative;
        height: max-content;
        top: calc(50% - 263px);
    }

    @media (max-width: 960px) {
        .storefront-wrapper {
            margin-left: inherit;
        }
    }

</style>

<div class="storefront-wrapper" uk-grid>
    <div class="cell uk-width-1-2@m uk-visible@m" uk-scrollspy="cls:uk-animation-slide-left-medium">
        <!-- /assets/business.svg https://getuikit.com/docs/image -->
        <img data-src="/assets/business.svg" width="100%" alt="Immeublify" uk-img>
    </div>
    <div class="cell uk-width-1-2@m uk-width-1-1@s uk-padding-large uk-padding-remove-top uk-padding-remove-bottom" uk-scrollspy="cls:uk-animation-slide-bottom-medium">
        <!-- https://getuikit.com/docs/heading -->
        <h1 class="uk-heading-small nunito">Achetez et vendez des immeubles à la vitesse de la lumière</h1>

        <!-- https://getuikit.com/docs/text -->
        <div class="uk-text-lead uk-margin-medium-bottom">Ne perdez plus de temps à rechercher des vendeurs et des acheteurs pour vos immeubles</div>

        <!-- https://getuikit.com/docs/form -->
        <form>
            <div class="uk-margin nunito">
                <input class="uk-input" type="text" placeholder="Nom">
            </div>
            <div class="uk-margin nunito">
                <input class="uk-input" type="text" placeholder="Adresse e-mail">
            </div>
            <button class="uk-button uk-button-primary uk-width-1-1 nunito">Créer votre compte</button>
            <div class="uk-margin">
                <label><input class="uk-checkbox" type="checkbox"> J'accepte les conditions générales d'utilisation. </label>
            </div>
        </form>

    </div>
</div>