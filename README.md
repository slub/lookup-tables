# lookup-tables

lookup tables ((mainly) two columns CSV files)

* [lookup_-_iso-639-1-code_to_language-name.csv](lookup/lookup_-_iso-639-1-code_to_language-name.csv): a (simple) translation from [ISO-639-1 codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) to corresponding (English) language names
   * dervided from [language-codes-full.csv](https://datahub.io/core/language-codes/r/language-codes-full.csv) at [datahub.io](https://datahub.io), see [ISO Language Codes (639-1 and 693-2) and IETF Language Types](https://datahub.io/core/language-codes)
   * see also [Codes for the Representation of Names of Languages](https://www.loc.gov/standards/iso639-2/php/code_list.php)
* [lookup_-_hochschulfaechersystematik_to_finc_class_facet.csv](lookup/lookup_-_hochschulfaechersystematik_to_finc_class_facet.csv): a mapping from the values of [Hochschulfächersystematik](https://w3id.org/kim/hochschulfaechersystematik/scheme) (see also: [git repository](https://github.com/dini-ag-kim/hochschulfaechersystematik)) to the values of (the field) ```finc_class_facet```
* [lookup_-_hochschulfaechersystematik_to_fincclass_txtF_mv.csv](lookup/lookup_-_hochschulfaechersystematik_to_fincclass_txtF_mv.csv): a mapping from the values of [Hochschulfächersystematik](https://w3id.org/kim/hochschulfaechersystematik/scheme) (see also: [git repository](https://github.com/dini-ag-kim/hochschulfaechersystematik)) to the values of (the field) ```fincclass_txtF_mv```
* [lookup_-_hochschulcampus_ressourcentypen_to_format_de14.csv](lookup/lookup_-_hochschulcampus_ressourcentypen_to_format_de14.csv): a mapping from the values of [Hochschulcampus Ressourcentypen](https://w3id.org/kim/hcrt/scheme) (see also: [git repository](https://github.com/dini-ag-kim/hcrt)) to the values of (the field) ```format_de14```
* [lookup_-_hochschulcampus_ressourcentypen_to_format.csv](lookup/lookup_-_hochschulcampus_ressourcentypen_to_format.csv): a mapping from the values of [Hochschulcampus Ressourcentypen](https://w3id.org/kim/hcrt/scheme) (see also: [git repository](https://github.com/dini-ag-kim/hcrt)) to the values of (the field) ```format```
* [opal_kurssprache_to_iso-639-1-code.csv](lookup/opal_kurssprache_to_iso-639-1-code.csv): a (simple) translation from values of the field ```kurssprache``` in [OPAL](https://bildungsportal.sachsen.de/opal/) learning resources to [ISO-639-1 codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
* [opal_license_to_license_uri.csv](lookup/opal_license_to_license_uri.csv): a (simple) translation from values of the field ```license``` in [OPAL](https://bildungsportal.sachsen.de/opal/) learning resources to their respective license URIs
* [opal_resourcetype_to_hcrt_uri.csv](lookup/opal_resourcetype_to_hcrt_uri.csv): a mapping from values of the field ```resourcetype``` in [OPAL](https://bildungsportal.sachsen.de/opal/) learning resources to values of [Hochschulcampus Ressourcentypen](https://w3id.org/kim/hcrt/scheme) (see also: [git repository](https://github.com/dini-ag-kim/hcrt))
* [hcrt.csv](lookup/hcrt.csv): a (simple) translation from [Hochschulcampus Ressourcentypen](https://w3id.org/kim/hcrt/scheme) URIs to their respective labels in German and English (see also: [git repository](https://github.com/dini-ag-kim/hcrt))

# lists

lists with values (one column CSV files)

* [articles.csv](lists/articles.csv): a list of articles
