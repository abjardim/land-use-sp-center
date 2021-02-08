# land-use-sp-center
Land Use Map of São Paulo's Old Downtown based on the course [Mapping Urban Data](http://morphocode.com) from Morphocode.

## Data Source
[GeoSampa](http://geosampa.prefeitura.sp.gov.br/PaginasPublicas/_SBC.aspx#)

## Methodology
Each lot's SQL number was matched with the IPTU 2020 to find its land use/owner. 
Names of owners were kept private when they were natural persons.
The land use types were separated into the categories in English as follows:

* *One & Two Family Buildings:* Residência; Residência coletiva, exclusive cortiço (mais de uma residência no lote); Cortiço 
* *Multi-Family Buildings:* Apartamento em condomínio; Prédio de apartamento, não em condomínio, de uso exclusivamente residencial; Flat residencial em condomínio; Garagem (unidade autônoma) em edifício em condomínio de uso exclusivamente residencial 
* *Mixed Residential & Commercial Buildings:* Loja e residência (predominância comercial); Prédio de apartamento, não em condomínio, de uso misto (apartamentos e escritórios e/ou consultórios), com ou sem loja (predominância residencial); Residência e outro uso (predominância residencial); Prédio de escritório, não em condomínio, de uso misto (apartamentos e escritórios e/ou consultórios) com ou sem loja (predominância comercial) 
* *Commercial & Office Buildings:* Loja; Outras edificações de uso comercial, com utilização múltipla; Loja em edifício em condomínio (unidade autônoma); Prédio de escritório ou consultório, não em condomínio, com ou sem lojas; Escritório/consultório em condomínio (unidade autônoma); Estação radioemissora, de televisão ou empresa jornalística; Cinema, teatro, casa de diversão, clube ou congênere; Garagem (unidade autônoma) em edifício em condomínio de escritórios, consultórios ou misto
* *Industrial & Manufacturing:* Indústria; Armazéns gerais e depósitos; Oficina 
* *Transportation & Utility:* Posto de serviço; Hotel, pensão ou hospedaria; Outras edificações de uso de serviço, com utilização múltipla; Flat de uso comercial (semelhante a hotel)
* *Public Facilities & Institutions:* Hospital, ambulatório, casa de saúde e assemelhados; Escola; Asilo, orfanato, creche, seminário ou convento; Templo 
* *Open Space & Outdoor Recreation:* Clube esportivo; Outras edificações de uso especial, com utilização múltipla; Outras edificações de uso coletivo, com utilização múltipla 
* *Parking Facilities:* Garagem (exclusive em prédio em condomínio); Garagem (unidade autônoma) de prédio de garagens 
* *Vacant Land:* Terreno 



