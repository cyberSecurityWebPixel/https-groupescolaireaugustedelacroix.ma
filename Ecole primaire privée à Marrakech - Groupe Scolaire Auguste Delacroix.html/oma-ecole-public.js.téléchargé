(function( $ ) {
	'use strict';

	/**
	 * All of the code for your public-facing JavaScript source
	 * should reside in this file.
	 *
	 * Note: It has been assumed you will write jQuery code here, so the
	 * $ function reference has been prepared for usage within the scope
	 * of this function.
	 *
	 * This enables you to define handlers, for when the DOM is ready:
	 *
	 * $(function() {
	 *
	 * });
	 *
	 * When the window is loaded:
	 *
	 * $( window ).load(function() {
	 *
	 * });
	 *
	 * ...and/or other possibilities.
	 *
	 * Ideally, it is not considered best practise to attach more than a
	 * single DOM-ready or window-load handler for a particular page.
	 * Although scripts in the WordPress core, Plugins and Themes may be
	 * practising this, we should strive to set a better example in our own work.
	 */

	 function toSecondForm() {
		 var firstForm = $('#first-step');
		 var secondForm = $('#second-step');
		 var tl = new TimelineMax();

		 tl.to(firstForm, 1, {x: "-3000px", autoAlpha:0, display:'none', ease:Power2.easeInOut});
		 tl.fromTo(secondForm, 1, {x:"3000px", autoAlpha:0, display:'none', ease:Power2.easeInOut}, {x:0, autoAlpha:1, display:'block', ease:Power2.easeInOut}, '-=0.9');

	 }

	 $(function() {

		 // Step form
 		$('input[name=demande_type]').click(function() {

 			var inputProcedure = $('input[name=demande_type]:checked').val();
 			if (inputProcedure == 'Inscription') {
 				$('.show-inscription').show();
 				$('.hide-inscription').hide();

 				//$('.demande_txt').text('d\'inscription');
 				$('select[name=date_test]').attr('required', true);
				// 09/04/2018
				$('.only-reinscription input[name=re_nom_enfant]').attr('required', false);
				$('.only-reinscription input[name=re_prenom_enfant]').attr('required', false);
				$('.only-reinscription input[name=re_nom_responsable_1]').attr('required', false);
				$('.only-reinscription input[name=re_prenom_responsable_1]').attr('required', false);
				$('.only-reinscription input[name=re_nom_responsable_2]').attr('required', false);
				$('.only-reinscription input[name=re_prenom_responsable_2]').attr('required', false);

				$('.only-reinscription select[name=re_classe_enfant]').attr('required', false);
				// Inscription
 			}else{
 				$('.show-inscription').hide();
 				//$('.demande_txt').text('de rÃ©inscription');
 				$('select[name=date_test]').attr('required', false);
				// 09/04/2018
				$('.only-reinscription input[name=re_nom_enfant]').attr('required', true);
				$('.only-reinscription input[name=re_prenom_enfant]').attr('required', true);
				$('.only-reinscription input[name=re_nom_responsable_1]').attr('required', true);
				$('.only-reinscription input[name=re_prenom_responsable_1]').attr('required', true);
				$('.only-reinscription input[name=re_nom_responsable_2]').attr('required', true);
				$('.only-reinscription input[name=re_prenom_responsable_2]').attr('required', true);
				//inscription
				$('.only-inscription select[name=classe_enfant]').attr('required', false);
				$('.only-inscription .cls_sexe_enfant').attr('required', false);
				$('.only-inscription input[name=nom_enfant]').attr('required', false);
				$('.only-inscription input[name=prenom_enfant]').attr('required', false);
				$('.only-inscription input[name=date_naissance_enfant]').attr('required', false);
				$('.only-inscription input[name=ville_naissance_enfant]').attr('required', false);
				$('.only-inscription input[name=pays_naissance_enfant]').attr('required', false);
				$('.only-inscription input[name=nationalite_1_enfant]').attr('required', false);
				$('.only-inscription input.cls_langue_maitrisees').attr('required', false);
				$('.only-inscription input[name=statut_responsable_1]').attr('required', false);
				$('.only-inscription input[name=nom_responsable_1]').attr('required', false);
				$('.only-inscription input[name=prenom_responsable_1]').attr('required', false);
				$('.only-inscription input[name=tel_responsable_1]').attr('required', false);
				$('.only-inscription input[name=email_responsable_1]').attr('required', false);
				$('.only-inscription input[name=cin_responsable_1]').attr('required', false);
				$('.only-inscription input[name=profession_responsable_1]').attr('required', false);
				$('.only-inscription input[name=adresse_responsable_1]').attr('required', false);
				$('.only-inscription input[name=code_postale_responsable_1]').attr('required', false);
				$('.only-inscription input[name=ville_responsable_1]').attr('required', false);
				$('.only-inscription input[name=ville_responsable_1]').attr('required', false);
				// Second fom inscription
				$('.only-inscription input[name=frere_soeur]').attr('required', false);
				$('.only-inscription .vaccin_ajour').attr('required', false);
				$('.only-inscription input[class=trouble_apprentissage]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_1_nom]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_1_prenom]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_1_tel]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_1_email]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_2_nom]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_2_prenom]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_2_tel]').attr('required', false);
				$('.only-inscription input[name=pers_joindre_2_email]').attr('required', false);
				$('.only-inscription input[name=pers_autoriser_1_nom]').attr('required', false);
				$('.only-inscription input[name=pers_autoriser_1_prenom]').attr('required', false);
				$('.only-inscription input[name=pers_autoriser_1_tel]').attr('required', false);
				$('.only-inscription input[name=pers_autoriser_1_cin]').attr('required', false);
				$('.only-inscription input[name=plateau_repas]').attr('required', false);
				$('.only-inscription input[name=autor_coordonees]').attr('required', false);
				$('.only-inscription input[name=droit_image]').attr('required', false);
				$('.only-inscription input[name=sortie_voyage]').attr('required', false);
				$('.only-inscription input[name=decharge_medical]').attr('required', false);
				$('.only-inscription input[name=reglement_interieur]').attr('required', false);

				// Réinscription 09/04/2018
				$('.status_reinscription').on('change', function () {
					if ( $(this).prop('checked') ) {
						$('.child-wrapper.reinscription').fadeIn();
						$('.child-wrapper.reinscription input').attr('required', true);
						$('.only-reinscription .re-classe').attr('required', true);
						$(this).val('OUI');
					} else {
						$('.child-wrapper.reinscription').hide();
						$('.child-wrapper.reinscription input').attr('required', false);
						$('.only-reinscription .re-classe').attr('required', false);
						$(this).val('NON');
					}
				});
 			}

 			TweenMax.set($('#second-step'),{display:"none"});
 			toSecondForm();

			//////////////////////////////// New JS Shit /////////////////////////////

			initPhoneInput();
			function initPhoneInput(){
				$('.nice-phone-picker').each(function() {
					$(this).inputmask("9 99 99 99 99");
					var inputName = $(this).attr('name');
					var phoneInput = $('input[name="'+inputName+'"]');
					$(phoneInput).intlTelInput({
						preferredCountries: ["ma", "fr"],
						separateDialCode: true,
						initialDialCode: true
					});
					var HiddenNumber = '<input type="hidden" class="nice-phone-child" name="'+inputName+'">';
					$(phoneInput).after(HiddenNumber);
				});
				$('.nice-phone-picker').blur(function () {
					var intPhone = '+' + $(this).intlTelInput('getSelectedCountryData').dialCode;
					intPhone += ' ' + $(this).val();
					$(this).next('.nice-phone-child').val(intPhone);
				});
			}

 			$('.selected-year').on('change',function(){
 				$('.change-year').html( $(this).val() );
 			});

 			$('input[name=demande_type]').on('change',function(e) {
 				e.preventDefault();
				var formType = $('input[name=demande_type]:checked').val();
	 			if (formType === 'Inscription' ) {
	 				$('.only-reinscription').remove();
	 			} else {
	 				$('.only-inscription').remove();
	 			}
 			});

 			var maxChild = 1;
 			$('.add-child.reinscription').on('click',function(e){

 				e.preventDefault();
 				if (maxChild == 4) {
 					console.log(maxChild);
 					alert('Maximum 4');
 					return;
 				}
 				
				var	data  = '<div class="delete">';
					data += '<hr>';
					data += '<div class="row mb-20">';
					data += 	'<div class="col-sm-2">';
					data += 		'<h4 class="mt-30">Enfant concerné:</h4>';
					data += 		'<a href="#" class="delete-child" nbr="'+maxChild+'">Supprimer</a>';
					data += 	'</div>';
					data += 	'<div class="col-sm-10">';
					data += 		'<div class="col-sm-6">';
					data += 			'<label>Nom:</label>';
					data += 			'<input type="text" name="rechild['+maxChild+'][re_nom_enfant]" class="form-control" required>';
					data += 		'</div>';
					data += 		'<div class="col-sm-6">';
					data += 			'<label>Prénom:</label>';
					data += 			'<input type="text" name="rechild['+maxChild+'][re_prenom_enfant]" class="form-control" required>';
					data += 		'</div>';
					data += 	'</div>';
					data += '</div>';
					data += '<div class="row mb-20">';
					data += 	'<div class="col-sm-2">';
					data += 		'<h4>Classe demandée:</h4>';
					data += 	'</div>';
					data += 	'<div class="col-sm-10">';
					data += 		'<div class="col-sm-12">';
					data += 			'<select class="form-control" name="rechild['+maxChild+'][re_classe_enfant]" required>';
					data += 				'<option value="" selected="">Choisissez la classe</option>';
					data += 				'<option value="CRECHE">Crèche</option>';
					data += 				'<option value="TPS">TPS</option>';
					data += 				'<option value="PS">PS</option>';
					data += 				'<option value="MS">MS</option>';
					data += 				'<option value="GS">GS</option>';
					data += 				'<option value="CE1">CE1 (CP)</option>';
					data += 				'<option value="CE2">CE2 (CE1)</option>';
					data += 				'<option value="CE3">CE3 (CE2)</option>';
					data += 				'<option value="CE4">CE4 (CM1)</option>';
					data += 				'<option value="CE5">CE5 (CM2)</option>';
					data += 				'<option value="CE6">CE6 (6)</option>';
					data += 				'<option value="1AC">1ère année collège</option>';
					data += 				'<option value="2AC">2ème année collège</option>';
					data += 			'</select>';
					data += 		'</div>';
					data += 	'</div>';
					data += '</div>';
					data += '</div>';

 				$('.child-wrapper.reinscription').append(data);
 				maxChild++;
		 		$('.child-wrapper.reinscription .delete-child').on('click',function(e){
		 			e.preventDefault();
			 		$(this).parent().parent().parent('.delete').find('hr').remove();
			 		$(this).parent().parent().parent('.delete').remove();
			 		maxChild--;
			 		return false;
		 		});
 			});

 			$('.add-child.inscription').on('click',function(e){

 				e.preventDefault();
 				if (maxChild == 4) {
 					console.log(maxChild);
 					alert('Maximum 4');
 					return;
 				}
 				
				var data  = '<div class="delete">';
					data += '<a href="#" class="delete-child" nbr="'+maxChild+'">Supprimer</a>';
					data += '	<hr>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label for="">Demande d\'inscription en : <span class="text-danger">*</span></label>';
					data += '				<select class="form-control" name="child['+maxChild+'][classe_enfant]" required>';
					data += '					<option></option>';
					data += '					<option value="CRECHE">Crèche</option>';
					data += '					<option value="TS">TS</option>';
					data += '					<option value="PS">PS</option>';
					data += '					<option value="MS">MS</option>';
					data += '					<option value="GS">GS</option>';
					data += '					<option value="CE1">CE1 (CP)</option>';
					data += '					<option value="CE2">CE2 (CE1)</option>';
					data += '					<option value="CE3">CE3 (CE2)</option>';
					data += '					<option value="CE4">CE4 (CM1)</option>';
					data += '					<option value="CE5">CE5 (CM2)</option>';
					data += '					<option value="CE6">CE6 (6)</option>';
					data += '				</select>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label for="" class="display-block">Sexe : <span class="text-danger">*</span></label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][sexe_enfant]" class="cls_sexe_enfant" value="F" required>';
					data += '					<i class="fa fa-female" aria-hidden="true"></i> Fille';
					data += '				</label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][sexe_enfant]" value="M">';
					data += '					<i class="fa fa-male" aria-hidden="true"></i> Garçon';
					data += '				</label>';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label>Nom de l\'enfant : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][nom_enfant]" class="form-control" required>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label>Prénom de l\'enfant : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][prenom_enfant]" class="form-control" required>';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label>Né(e) le : <span class="text-danger">*</span></label>';
					data += '				<div class="input-group">';
					data += '					<input type="text" name="child['+maxChild+'][date_naissance_enfant]" id="date_naissance_enfant" class="form-control" required>';
					data += '					<span class="input-group-addon"><i class="fa fa-calendar" aria-hidden="true"></i></span>';
					data += '				</div>';
					data += '				<span class="help-block">Date de naissance</span>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>À : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][ville_naissance_enfant]" value="Marrakech" class="form-control" required>';
					data += '				<span class="help-block">Ville de naissance</span>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Pays : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][pays_naissance_enfant]" value="Maroc" class="form-control" required>';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label>Nationalité 1 : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][nationalite_1_enfant]" value="Marocaine" class="form-control" required>';
					data += '				<span class="help-block">EX : Marocaine, Française, ...</span>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label>Nationalité 2 :</label>';
					data += '				<input type="text" name="child['+maxChild+'][nationalite_2_enfant]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-12">';
					data += '			<legend><span class="glyphicon glyphicon-education" aria-hidden="true"></span> Scolarité antérieure</legend>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-4">';
					data += '			<div class="form-group">';
					data += '				<label>Année scolaire :</label>';
					data += '				<input type="text" name="child['+maxChild+'][annee_scolaire_1]" id="annee_scolaire_1" class="form-control mask-annee">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-4">';
					data += '			<div class="form-group">';
					data += '				<label>Établissement :</label>';
					data += '				<input type="text" name="child['+maxChild+'][etablissement_1]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-4">';
					data += '			<div class="form-group">';
					data += '				<label>Niveau :</label>';
					data += '				<input type="text" name="child['+maxChild+'][niveau_1]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '<div class="row">';
					data += '	<div class="col-md-12">';
					data += '		<div class="form-group">';
					data += '			<label class="display-block">';
					data += '				<i class="fa fa-language" aria-hidden="true"></i> Langues maitrisées : <span class="text-danger">*</span>';
					data += '			</label>';
					data += '			<label class="checkbox-inline">';
					data += '				<input type="checkbox" name="child['+maxChild+'][langues_maitrisee][]" class="cls_langue_maitrisees" value="AR" required> Arabe';
					data += '			</label>';
					data += '			<label class="checkbox-inline">';
					data += '				<input type="checkbox" name="child['+maxChild+'][langues_maitrisee][]" value="FR"> Français';
					data += '			</label>';
					data += '			<label class="checkbox-inline">';
					data += '				<input type="checkbox" name="child['+maxChild+'][langues_maitrisee][]" value="EN"> Anglais';
					data += '			</label>';
					data += '			<label class="checkbox-inline">';
					data += '				<input type="checkbox" name="child['+maxChild+'][trigger_langues_autres]" id="trigger_langues_autres" value="AUTRES"> Autres';
					data += '			</label>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="col-md-12" id="langues_maitrisees_autres">';
					data += '		<div class="form-group">';
					data += '			<label>Préciser les autres langues : <span class="text-danger">*</span></label>';
					data += '			<input type="text" name="child['+maxChild+'][langues_maitrisees_autres]" class="form-control">';
					data += '		</div>';
					data += '	</div>';
					data += '</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-12">';
					data += '			<div class="form-group">';
					data += '				<label for="" class="display-block">L\'élève a-t-il des frères et soeurs : <span class="text-danger">*</span></label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][frere_soeur]" value="OUI" required> Oui';
					data += '				</label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][frere_soeur]" value="NON"> Non';
					data += '				</label>';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row frere-container">';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Prénom : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_1_prenom]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Age : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_1_age]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Établissement : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_1_etablissement]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Classe : <span class="text-danger">*</span></label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_1_classe]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row frere-container">';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Prénom :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_2_prenom]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Age :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_2_age]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Établissement :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_2_etablissement]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Classe :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_2_classe]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row frere-container">';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Prénom :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_3_prenom]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Age :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_3_age]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Établissement :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_3_etablissement]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Classe :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_3_classe]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row frere-container">';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Prénom :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_4_prenom]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Age :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_4_age]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Établissement :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_4_etablissement]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-3">';
					data += '			<div class="form-group">';
					data += '				<label>Classe :</label>';
					data += '				<input type="text" name="child['+maxChild+'][frere_4_classe]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-12">';
					data += '			<legend><i class="fa fa-medkit" aria-hidden="true"></i> Renseignements médicaux</legend>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label>Nom du medecin traitant de l\'enfant :</label>';
					data += '				<input type="text" name="child['+maxChild+'][medecin_traitant_nom]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label class="display-block">Téléphone :</label>';
					data += '				<input type="tel" name="child['+maxChild+'][medecin_traitant_tel]" class="form-control">';
					data += '				<input type="hidden" name="child['+maxChild+'][medecin_traitant_tel]">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label for="" class="display-block">Vaccin obligatoire à jour : <span class="text-danger">*</span></label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][vaccin_ajour]" value="OUI" required> Oui';
					data += '				</label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][vaccin_ajour]" value="NON"> Non';
					data += '				</label>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-6 vaccion_description">';
					data += '			<div class="form-group">';
					data += '				<label>Lesquels :</label>';
					data += '				<input type="text" name="child['+maxChild+'][vaccin_ajour_lesquels]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-12">';
					data += '			<div class="form-group">';
					data += '				<label>Allergies alimentaires ou autres :</label>';
					data += '				<input type="text" name="child['+maxChild+'][allergies]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-12">';
					data += '			<div class="form-group">';
					data += '				<label>Maladie chronique éventuelle :</label>';
					data += '				<input type="text" name="child['+maxChild+'][maladie_chroniques]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-6">';
					data += '			<div class="form-group">';
					data += '				<label for="" class="display-block">Trouble d\'apprentissage éventuel : <span class="text-danger">*</span></label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" class="trouble_apprentissage" name="child['+maxChild+'][trouble_apprentissage]" value="OUI" required> Oui';
					data += '				</label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" class="trouble_apprentissage" name="child['+maxChild+'][trouble_apprentissage]" value="NON"> Non';
					data += '				</label>';
					data += '			</div>';
					data += '		</div>';
					data += '		<div class="col-md-6 trouble_description">';
					data += '			<div class="form-group">';
					data += '				<label>Lequel :</label>';
					data += '				<input type="text" name="child['+maxChild+'][trouble_apprentissage_lequel]" class="form-control">';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row trouble_description">';
					data += '		<div class="col-md-12">';
					data += '			<div class="form-group">';
					data += '				<label for="" class="display-block">Suivi par un spécialiste : <span class="text-danger">*</span></label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" class="trouble_app_suivi" name="child['+maxChild+'][trouble_app_suivi]" value="OUI"> Oui';
					data += '				</label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" class="trouble_app_suivi" name="child['+maxChild+'][trouble_app_suivi]" value="NON"> Non';
					data += '				</label>';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row flash-info-specialiste">';
					data += '		<div class="col-md-12">';
					data += '			<div class="alert alert-info" role="alert">Veuillez déposer lors de votre retour au secrétariat une copie du dossier utile à l\'école</div>';
					data += '		</div>';
					data += '	</div>';
					data += '	<div class="row">';
					data += '		<div class="col-md-12">';
					data += '			<div class="form-group">';
					data += '				<label for="" class="display-block">Plateau repas chaud et garderie 12h-14h souhaitée : <span class="text-danger">*</span></label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][plateau_repas]" value="OUI" required> Oui';
					data += '				</label>';
					data += '				<label class="radio-inline">';
					data += '					<input type="radio" name="child['+maxChild+'][plateau_repas]" value="NON"> Non';
					data += '				</label>';
					data += '				<span class="help-block">(Plateau repas les lundis, mardis, jeudis et vendredis ; inscription au trimestre)</span>';
					data += '			</div>';
					data += '		</div>';
					data += '	</div>';
					data += '</div>';

 				$('.child-wrapper.inscription').append(data);
 				maxChild++;
		 		$('.child-wrapper.inscription .delete-child').on('click',function(e){
		 			e.preventDefault();
			 		$(this).parent().parent().parent('.delete').find('hr').remove();
			 		$(this).parent().parent().parent('.delete').remove();
			 		maxChild--;
			 		return false;
		 		});
 			});
 		});
	

		///////////////// new shit
		// Datepicker date de naissance
/*		$('#date_naissance_enfant').datepicker({
			format: "dd/mm/yyyy",
			endDate: "today",
			language: "fr",
			startView: 2,
			autoclose: true,
			todayHighlight: true
		});*/

		// Datepicker date de naissance
		initDatePicker();
		function initDatePicker()
		{
			$('.nice-date-picker').datepicker({
				format: "dd/mm/yyyy",
				endDate: "today",
				language: "fr",
				startView: 2,
				autoclose: true,
				todayHighlight: true
			});
		}

		// Mask input année scolaire
		$('.mask-annee').inputmask("9999-9999");

		// Langues maitrisées (autres)
		$('#trigger_langues_autres').on('click', function () {
			if ($(this).prop('checked')) {
				$('#box_langues_maitrisee_autres').fadeIn();
				$('.langues_maitrisees_autres').attr('required', true);
			} else {
				$('#box_langues_maitrisee_autres').hide();
				$('.langues_maitrisees_autres').attr('required', false);
			}
		});


		/*
		// Indicatif téléphone responsable 1
		$('#responsable_1_tel').inputmask("9 99 99 99 99");
		$('#responsable_1_tel').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#responsable_1_tel').blur(function () {
			$('input[name=tel_responsable_1]').val('+ ' + $('#responsable_1_tel').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#responsable_1_tel').val());
		});
		// indicatif responsable 1 autre
		$('#responsable_1_tel_autre').inputmask("9 99 99 99 99");
		$('#responsable_1_tel_autre').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#responsable_1_tel_autre').blur(function () {
			$('input[name=tel_autre_responsable_1]').val('+ ' + $('#responsable_1_tel_autre').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#responsable_1_tel_autre').val());
		});

		*/

		/*
		// Indicatif téléphone responsable 2
		$('#tel_responsable_2_picker').inputmask("9 99 99 99 99");
		$('#tel_responsable_2_picker').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#tel_responsable_2_picker').blur(function () {
			$('input[name=tel_responsable_2]').val('+ ' + $('#tel_responsable_2_picker').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#tel_responsable_2_picker').val());
		});
		*/
		// indicatif responsable 2 autre

		/*
		$('#tel_autre_responsable_2_picker').inputmask("9 99 99 99 99");
		$('#tel_autre_responsable_2_picker').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#tel_autre_responsable_2_picker').blur(function () {
			$('input[name=tel_autre_responsable_2]').val('+ ' + $('#tel_autre_responsable_2_picker').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#tel_autre_responsable_2_picker').val());
		});
		*/

		// Responsable 2 make required if entered name
		$('input[name=nom_responsable_2]').blur(function() {
			var input_value = $("input[name=nom_responsable_2]").val();
			if(input_value != '') {
				$('input[name=statut_responsable_2]').attr('required', true);
				$('input[name=nom_responsable_2]').attr('required', true);
				$('input[name=prenom_responsable_2]').attr('required', true);
				$('input[name=tel_responsable_2]').attr('required', true);
				$('input[name=email_responsable_2]').attr('required', true);
				$('input[name=cin_responsable_2]').attr('required', true);
				$('input[name=profession_responsable_2]').attr('required', true);
				$('input[name=adresse_responsable_2]').attr('required', true);
				$('input[name=code_postale_responsable_2]').attr('required', true);
				$('input[name=ville_responsable_2]').attr('required', true);

				$('input[name=nom_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=prenom_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=tel_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=email_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=cin_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=profession_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=adresse_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=code_postale_responsable_2]').prevAll('label').children('span').removeClass('hidden');
				$('input[name=ville_responsable_2]').prevAll('label').children('span').removeClass('hidden');
			}else{
				$('input[name=statut_responsable_2]').attr('required', false);
				$('input[name=nom_responsable_2]').attr('required', false);
				$('input[name=prenom_responsable_2]').attr('required', false);
				$('input[name=tel_responsable_2]').attr('required', false);
				$('input[name=email_responsable_2]').attr('required', false);
				$('input[name=cin_responsable_2]').attr('required', false);
				$('input[name=profession_responsable_2]').attr('required', false);
				$('input[name=adresse_responsable_2]').attr('required', false);
				$('input[name=code_postale_responsable_2]').attr('required', false);
				$('input[name=ville_responsable_2]').attr('required', false);

				$('input[name=nom_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=prenom_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=tel_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=email_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=cin_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=profession_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=adresse_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=code_postale_responsable_2]').prevAll('label').children('span').addClass('hidden');
				$('input[name=ville_responsable_2]').prevAll('label').children('span').addClass('hidden');
			}
		});

		// Validation js to all form
		$('#oma-public-form').validate({
			ignore: 'input[type=hidden]',
			errorPlacement: function(error, element){

				// Unstyled checkboxes, radios
				if (element.parents('div').hasClass('checkbox') || element.parents('div').hasClass('radio')) {
					error.appendTo( element.parent().parent().parent() );
				}

				// Input with icons and Select2
				else if (element.parents('div').hasClass('has-feedback') || element.hasClass('select2-hidden-accessible')) {
					error.appendTo( element.parent() );
				}

				// Inline checkboxes, radios
				else if (element.parents('label').hasClass('checkbox-inline') || element.parents('label').hasClass('radio-inline')) {
					error.appendTo( element.parent().parent() );
				}

				// Input group, styled file input
				else if (element.parent().hasClass('uploader') || element.parents().hasClass('input-group')) {
					error.appendTo( element.parent().parent() );
				}

				// Input indicatif
				else if (element.parent().hasClass('intl-tel-input')) {
					error.appendTo( element.parent().parent() );
				}

				else {
					error.insertAfter(element);
				}
				// end
			},
			messages: {
				classe_enfant: "Vous devez préciser la classe",
				sexe_enfant: "Vous devez choisir le sexe de l'enfant"
			}
		});

		// Second Private form ==============================================
		// Frères et soeurs
	    $('input[name=frere_soeur]').on('click', function () {
	        var inputFreres = $('input[name=frere_soeur]:checked').val();
	        if (inputFreres == 'OUI') {
	            $('.frere-container').show();
	        }else{
	            $('.frere-container').hide();
	        }
	    });
		// Vaccin à jour si non lesquels
	    $('.vaccin_ajour').on('click', function () {
	        var inputVaccin = $('.vaccin_ajour:checked').val();
	        if (inputVaccin == 'NON') {
	            $('.vaccion_description').show();
	        }else{
	            $('.vaccion_description').hide();
	        }
	    });
		// Trouble d'apprentissage
	    $('input[class=trouble_apprentissage]').on('click', function () {
	        var inputTrouble = $('input[class=trouble_apprentissage]:checked').val();
	        if (inputTrouble == 'OUI') {
	            $('.trouble_description').show();
	            //$('.frere-container').first().css('background', 'red');
	        }else{
	            $('.trouble_description').hide();
	        }
	    });
		// Suivie par un spécialiste (Alert info dossier au secretariat)
	    $('input[class=trouble_app_suivi]').on('click', function () {
	        var inputTroubleSpe = $('input[class=trouble_app_suivi]:checked').val();
	        if (inputTroubleSpe == 'OUI') {
	            $('.flash-info-specialiste').show();
	            //$('.frere-container').first().css('background', 'red');
	        }else{
	            $('.flash-info-specialiste').hide();
	        }
	    });
		// Indicatif téléphone Personne à joindre 1
		/*
		$('#pers_joindre_1_tel_picker').inputmask("9 99 99 99 99");
		$('#pers_joindre_1_tel_picker').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#pers_joindre_1_tel_picker').blur(function () {
			$('input[name=pers_joindre_1_tel]').val('+ ' + $('#pers_joindre_1_tel_picker').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#pers_joindre_1_tel_picker').val());
		});
		*/
		// Indicatif téléphone Personne à joindre 2

		/*
		$('#pers_joindre_2_tel_picker').inputmask("9 99 99 99 99");
		$('#pers_joindre_2_tel_picker').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#pers_joindre_2_tel_picker').blur(function () {
			$('input[name=pers_joindre_2_tel]').val('+ ' + $('#pers_joindre_2_tel_picker').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#pers_joindre_2_tel_picker').val());
		});
		*/
		// Indicatif téléphone Personne autoriser 1
		/*
		$('#pers_autoriser_1_tel_picker').inputmask("9 99 99 99 99");
		$('#pers_autoriser_1_tel_picker').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#pers_autoriser_1_tel_picker').blur(function () {
			$('input[name=pers_autoriser_1_tel]').val('+ ' + $('#pers_autoriser_1_tel_picker').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#pers_autoriser_1_tel_picker').val());
		});
		*/

		// Indicatif téléphone Personne autoriser 1
		/*
		$('#pers_autoriser_2_tel_picker').inputmask("9 99 99 99 99");
		$('#pers_autoriser_2_tel_picker').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#pers_autoriser_2_tel_picker').blur(function () {
			$('input[name=pers_autoriser_2_tel]').val('+ ' + $('#pers_autoriser_2_tel_picker').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#pers_autoriser_2_tel_picker').val());
		});
		*/
		/*
		// Indicatif téléphone Médecin traitant
		$('#medecin_traitant_tel').inputmask("9 99 99 99 99");
		$('#medecin_traitant_tel').intlTelInput({
			preferredCountries: ["ma", "fr"],
			initialDialCode: true,
			separateDialCode: true
		});
		$('#medecin_traitant_tel').blur(function () {
			$('input[name=medecin_traitant_tel]').val('+ ' + $('#medecin_traitant_tel').intlTelInput("getSelectedCountryData").dialCode + ' ' + $('#medecin_traitant_tel').val());
		});
		*/
		// Décharge médicale
	    $('input[name=decharge_medical]').on('click', function () {
	        var inputDecharge = $('input[name=decharge_medical]:checked').val();
	        if (inputDecharge == 'NON') {
	            $('.decharge_medical_description').show();
	        }else{
	            $('.decharge_medical_description').hide();
	        }
	    });

		// Validation js to all form
		$('#oma-private-form').validate({
			ignore: 'input[type=hidden]',
			errorPlacement: function(error, element){

				// Unstyled checkboxes, radios
				if (element.parents('div').hasClass('checkbox') || element.parents('div').hasClass('radio')) {
					error.appendTo( element.parent().parent().parent() );
				}

				// Input with icons and Select2
				else if (element.parents('div').hasClass('has-feedback') || element.hasClass('select2-hidden-accessible')) {
					error.appendTo( element.parent() );
				}

				// Inline checkboxes, radios
				else if (element.parents('label').hasClass('checkbox-inline') || element.parents('label').hasClass('radio-inline')) {
					error.appendTo( element.parent().parent() );
				}

				// Input group, styled file input
				else if (element.parent().hasClass('uploader') || element.parents().hasClass('input-group')) {
					error.appendTo( element.parent().parent() );
				}

				// Input indicatif
				else if (element.parent().hasClass('intl-tel-input')) {
					error.appendTo( element.parent().parent() );
				}

				else {
					error.insertAfter(element);
				}
				// end
			},
			// messages: {
			// 	classe_enfant: "Vous devez préciser la classe",
			// 	sexe_enfant: "Vous devez choisir le sexe de l'enfant"
			// }
		});

	}); // End $.function

})( jQuery );
