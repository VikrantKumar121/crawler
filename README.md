# WebScrapping

---
Run country_codes_scraper.py for parsing HTML and storing into output.txt

```python
python country_codes_scraper.py -o output.txt     
```
Run country_data_codes.py for specifiec output
```python
data = CountryDataCodes('output.txt')
data.get_all_country_name()
data.get_country_details('[countryname]')   
data.get_country_name('[countryname]')  
```

>"Just replace [countryname] with any country name and get output"

## **Developed by:** Vikrant Kumar
### **Script Version:** V1.0
