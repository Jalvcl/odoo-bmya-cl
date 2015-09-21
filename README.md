[![Build Status](https://travis-ci.org/odoo-chile/l10n_cl_financial_indicators.svg?branch=8.0)](https://travis-ci.org/odoo-chile/l10n_cl_financial_indicators)
[![Coverage Status](https://coveralls.io/repos/odoo-chile/l10n_cl_financial_indicators/badge.png?branch=8.0)](https://coveralls.io/r/odoo-chile/l10n_cl_financial_indicators?branch=8.0)

Odoo - Update Chilean Financial Indicators
==========================================

Module that updates the following indicators used in Chile for Odoo
sofware:

Dollar
Euro
UF
UTM

It connects to SBIFs webservices. Prior to use, you must get your
own apikey from this webpage:

An then replace it at:

apikey.py
(rename apikey.py.sample to apikey.py and include your own api key there)

You must also have the following these currency values loaded in your 
system, using the following Id for each one:

USD
EUR
UF
UTM

If the spell is not the same, this implementation won't be able to find
the currencies or the indexes to update.
 
Actualizador de indices financieros chilenos para Odoo
======================================================

Este módulo de Odoo, actualiza los siguientes indicadores usados en Chile:

Dolar
Euro
UF
UTM

Se conecta a los webservices provistos por la Superintendencia de Bancos
e Instituciones Financieras de Chile - SBIF, para obtener los valores 
oficiales del día.
Previo al uso, Ud. debe obtener su propia clave de API
desde esta página web:

http://api.sbif.cl/api/contactanos.jsp

Y entonces, reemplazar la misma en:

apikey.py

(renombra apikey.py.sample a apikey.py e incluye allí tu propia clave api)

Ud. deberá tener las siguientes monedas ingresadas en su sistema Odoo,
utilizando la siguiente identificación para las mismas:

USD
EUR
UF
UTM

Si la nomenclatura no es exactamente la misma, esta implementacion
no podrá encontrar las monedas para ser actualizadas.
 
