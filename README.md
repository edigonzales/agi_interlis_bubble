# agi_interlis_bubble

```
java -jar /Users/stefan/apps/ili2pg-4.4.5/ili2pg-4.4.5.jar \
--dbhost localhost --dbport 54321 --dbdatabase edit --dbusr admin --dbpwd admin \
--dbschema afu_vsadssmini2020 --models VSADSSMINI_2020_LV95 --modeldir "https://vsa.ch/models" \
--defaultSrsCode 2056 --createGeomIdx --createFk --createFkIdx --createUnique --createEnumTabs --beautifyEnumDispName --createMetaInfo --createNumChecks --nameByTopic --strokeArcs \
--schemaimport
```

```
java -jar /Users/stefan/apps/ili2pg-4.4.5/ili2pg-4.4.5.jar \
--dbhost localhost --dbport 54321 --dbdatabase edit --dbusr admin --dbpwd admin \
--dbschema afu_vsadssmini2020 --models SIA405_Base_Abwasser_LV95 --modeldir "https://vsa.ch/models" \
--defaultSrsCode 2056 --strokeArcs \
--import vsa_organisationen.xtf
```


```
java -jar /Users/stefan/apps/ili2pg-4.4.5/ili2pg-4.4.5.jar \
--dbhost localhost --dbport 54321 --dbdatabase edit --dbusr admin --dbpwd admin \
--dbschema afu_vsadssmini2020 --models VSADSSMINI_2020_LV95 --modeldir "https://vsa.ch/models" \
--defaultSrsCode 2056 --strokeArcs \
--export knoten_organisationen.xtf
```