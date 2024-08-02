# webscrapping
The aim of these project is to scrape the model, product name, price and rating video graphics card  from newegg sales website. 
New egg is a sales website that deals with  sales of electrical and electronic appliances of various kinds. 
Step 1.
Pip install Beautifulsoup 4.
These library packeges pass html and xml codes w=when scraping.
Step 2
We imported the url request.
This is  used to open and read URLs, which is particularly useful in web scraping to fetch the HTML content of web pages.
Step 3. 
We use the html parser to import the webcontent in html.
Step 4.
A loop was written to call out each of the divs that contains the model, product name, price and ratings and it was saved in csv using this
filename = "produc.csv"
with open(filename, "w", encoding="utf-8") as f. 
