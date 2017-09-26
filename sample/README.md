## SAMPLE USAGE
Is necessary install portuguese language to tesseract
```bash
cd /usr/share/tesseract-ocr/tessdata/
wget https://github.com/tesseract-ocr/tessdata/raw/master/por.traineddata
```


```bash
extractor.py  --url https://github.com/petryx/pyextractor/raw/master/sample/teste-sambaqui-florianopolis.pdf --out sample_output.csv --config config.yml --lang por
```
