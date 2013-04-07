countries-states-name-rails
===========================

Countries and US States form helper fields for Ruby on Rails.
Usages
------
	countries_tag :form_field_name, value, options = {}
	us_states_tag :form_field_name, value, options = {}

Standard form tag adding any form

	from_for @model do |f|
		f.countries :model_field_name
	end

Generate drop down select field for model.  Value stored as country 2 letters initial.

	country_name_from_initial :initial

Retrieve a country's full name from it 2 letters initials

	us_state_name_from_initial :initial

Retrieve a full state name from it 2 letters initial

	ActionView::Helpers::CountriesNameHelper.countries
	ActionView::Helpers::USStatesNameHelper.states

Return a hash of the countries and states used for this helper.

License
-------
MIT License.  Use at your own risk.