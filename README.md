
si fudud ku hel xogaha dalalka adigoo isticmaalaya javascript

let dalka= require('dalalka')
var lookup = require('dalalka').lookup;

let wadamada=dalka.countries
console.log(wadamada.all)
// dalalka oo idil ayuu kuu soo saarayaa

let lacagaha = dalka.currencies.all
console.log(lacagaha)
// wuxuu kuu soo saaray lacagha dunida oo idil
var somalia = lookup.countries({name: 'somalia'})[0];
console.log(somalia)

{
    // alpha2: 'SO',
    // alpha3: 'SOM',
    // countryCallingCodes: [ '+252' ],
    // currencies: [ 'SOS' ],
    // emoji: '🇸🇴',
    // ioc: 'SOM',
    // languages: [ 'som' ],
    // name: 'Somalia',
    
