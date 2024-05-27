# Flipkart-Web-Scraping
From this python code i am scraping the specific flipkart page and i am gonna save the title and links of the product in the csv file.

this code will scrape all the product links and the title of the products which is given on [This link](https://www.flipkart.com/cameras/dslr-mirrorless/pr?sid=jek%2Cp31%2Ctrv&p%5B%5D=facets.fulfilled_by%255B%255D%3DFlipkart%2BAssured&p%5B%5D=facets.type%255B%255D%3DMirrorless&param=179&ctx=eyJjYXJkQ29udGV4dCI6eyJhdHRyaWJ1dGVzIjp7InZhbHVlQ2FsbG91dCI6eyJtdWx0aVZhbHVlZEF0dHJpYnV0ZSI6eyJrZXkiOiJ2YWx1ZUNhbGxvdXQiLCJpbmZlcmVuY2VUeXBlIjoiVkFMVUVfQ0FMTE9VVCIsInZhbHVlcyI6WyJTaG9wIE5vdyEiXSwidmFsdWVUeXBlIjoiTVVMVElfVkFMVUVEIn19LCJ0aXRsZSI6eyJtdWx0aVZhbHVlZEF0dHJpYnV0ZSI6eyJrZXkiOiJ0aXRsZSIsImluZmVyZW5jZVR5cGUiOiJUSVRMRSIsInZhbHVlcyI6WyJUb3AgTWlycm9ybGVzcyBDYW1lcmFzIl0sInZhbHVlVHlwZSI6Ik1VTFRJX1ZBTFVFRCJ9fSwiaGVyb1BpZCI6eyJzaW5nbGVWYWx1ZUF0dHJpYnV0ZSI6eyJrZXkiOiJoZXJvUGlkIiwiaW5mZXJlbmNlVHlwZSI6IlBJRCIsInZhbHVlIjoiRExMR1FBUVlOVDM5WkpURyIsInZhbHVlVHlwZSI6IlNJTkdMRV9WQUxVRUQifX19fX0%3D&page=1) and it will put them in the csv file.

This code probable won't on the online compilers, it might can work on google collab after installing the libraries and if you download the code and trying to run it just make sure to check the file path of the csv file in the code, add the path of your directory so it will not give and error plus check once if the GET response is 200 or not if its not 200 or 403,etc then it might possible the link or the user agent requirnments might be cchanged.

**To run the code:-**
install the required libraries:- (if you're running this code on windows then run these commands in the terminal)

```python
  pip install bs4
  pip install requests
  pip install pandas
```
