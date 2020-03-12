<style>

	.uk-logo {
		font-weight: 800;
	}

	.bg-white {
		background-color: white;
	}

	.uk-navbar-container {
		max-width: 80em;
		margin: auto;
		background-color: white;
	}

	.uk-navbar-nav > li > a {
		text-transform: inherit;
	}

</style>

<div class="bg-white" uk-sticky="sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky">
	<nav class="uk-navbar-container" uk-navbar>
		<div class="uk-navbar-left">
			<a href="/" class="uk-navbar-item uk-logo nunito">Immeublify</a>
		</div>
		<div class="uk-navbar-right">
			<ul class="uk-navbar-nav uk-visible@s">
				<li>
					<a class="nunito" href="javacript:void(0)">Entreprise</a>
					<div class="uk-navbar-dropdown">
						<ul class="uk-nav uk-navbar-dropdown-nav nunito">
							<li><a href="javacript:void(0)">Immeubles haut de gamme</a></li>
							<li><a href="javacript:void(0)">Clients</a></li>
							<li><a href="javacript:void(0)">Assurances</a></li>
						</ul>
					</div>
				</li>
				<li><a class="nunito" href="javacript:void(0)">Blog</a></li>
				<li><a class="nunito" href="javacript:void(0)">Support</a></li>
				<li><a class="nunito" href="javacript:void(0)"><span class="uk-button uk-button-primary">Demander un devis</span></a></li>
			</ul>
			<ul class="uk-navbar-nav uk-hidden@s">
				<li>
					<a href="javacript:void(0)"><i class="fas fa-bars"></i></a>
					<div class="uk-navbar-dropdown">
						<ul class="uk-nav uk-navbar-dropdown-nav nunito">
							<li><a href="javacript:void(0)">Entreprise</a></li>
							<li><a href="javacript:void(0)">Blog</a></li>
							<li><a href="javacript:void(0)">Support</a></li>
							<li><a class="nunito" href="javacript:void(0)"><span class="uk-button uk-button-primary">Demander un devis</span></a></li>
						</ul>
					</div>
				</li>
			</ul>
		</div>
	</nav>
</div>