# ETL-project


Overview
This project uses an established connection to MongoDB to web scrape the PokemonCenter website for items that have reviews and which item has the highest review. One issue that occurred is when the code runs, once the "browser.visit(url)" section is reached, the website requires a CAPTCHA. Which means that if the browser is opened from the code and the CAPTCHA isn't completed on the PokemonCenter website, then the code won't parser. The simple fix is to go to the site that opens and complete the CAPTCHA and rerun the parser.