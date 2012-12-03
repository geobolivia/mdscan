Ce travail est dérivé du simple CSW client du National Aerospace Laboratory NLR
website http://www.gdsc.nl/gdsc/en/tools/simple_csw_client

mdscan est un outil de vérification des métadonnées d'un catalogue par le protocole csw.
mdscan vérifie les informations transmises par csw pour vérifier qu'un client csw disposera
d'informations suffisantes pour présenter les données.

mdscan utilise :
 * sarissa              GNU GPLv3    http://dev.abiss.gr/sarissa/
 * sarissa ieemu xpath  GNU GPLv3
 * jquery               GNU GPLv2    http://jquery.org

Pour créer le fichier lib/xsl/csw-sample.xml
    www.geo.gob.bo/geonetwork/srv/es/csw?request=GetRecords&service=CSW&version=2.0.2&namespace=xmlns%28csw%3Dhttp%3A%2F%2Fwww.opengis.net%2Fcat%2Fcsw%2F2.0.2%29%2Cxmlns%28gmd%3Dhttp%3A%2F%2Fwww.isotc211.org%2F2005%2Fgmd%29&constraint=AnyText+like+%carreteras%&constraintLanguage=CQL_TEXT&constraint_language_version=1.1.0&typeNames=csw%3ARecord&ELEMENTSETNAME=full&RESULTTYPE=results
Plus de détails sur la page:
    http://dev.geonode.org/trac/wiki/CSW_GetRecords

mdscan est produit par geOrchestra
http://www.georchestra.og/

