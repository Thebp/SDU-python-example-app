# Website scraper
This is a simple service, that takes a link (string) and returns all text on the given website. 

It is called in this manner: 

- localhost:5000/?link=https://www.google.com

You need to set up a Dockerfile, which builds it.

Hint: 
- You need python (find a base image with python!)
- You need 
    * py-pip (PIP - python package manager)  
    * pip install -r requirements.txt 
- The app runs on port 6100
