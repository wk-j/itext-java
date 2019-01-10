## Java

```bash
mvn exec:java -Dexec.mainClass="Program"


java -jar editor-server-0.15.0.jar server config.yml

java -jar server/editor-server-1.0.0-SNAPSHOT.jar server server/config.yml

java -jar dito-batch-cli-0.15.0.jar -d in/ -k inbatek-workshop.xml -o out/ -p bangkok.dito

java -jar server/dito-batch-cli-0.15.0.jar \
    -d input \
    -k server/inbatek-workshop.xml \
    -o .output \
    -p server/bangkok.dito


java -jar pdf2data-cli-2.1.2.jar preprocess -t template.pdf -x template.xml -l itextkey1546527870812_0.xml
```