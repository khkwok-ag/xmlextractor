# xmlextractor
This is a tool to extract XML elements from XML file by tag. The ouput can be save into a file in txt, csv or xlsx format.

## Feature
* .txt, .csv, .xlsx output format supported
* nested elements supported
* n tags extraction supported (.txt ouput format only)

## Prerequisites
* lxml
 ```sh
 pip install lxml
 ```
 * panda
  ```
 pip install pandas
  ```
## Execution:
Run the following command to execute the program. The extraction output will be save into output file. It will be overwritten if the output exist.

* save into .txt
 ```sh
python3 xmlextractor.py <xml>.xml <tag> <output>.txt
 ```
 * save into .csv
 ```sh
python xmlextractor.py <xml>.xml <tag> <output>.csv
 ```
 * save into .xlsx
 ```sh
python xmlextractor.py <xml>.xml <tag> <output>.xlsx
 ```

* n tags extraction example (.txt only)
```sh
python xmlextractor.py <xml>.xml <tag1>,<tag2>,<tagN> <output>.txt
```

Update with more features prior to Come.
