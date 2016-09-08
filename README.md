# project-arbitrage
A data visualization protect to identify traffic flows associated with the largest arbitrage sites in the world.

### Getting Started 

1) Copy the contents of the repository to a folder in your computer or a server 

#### SERVER

2.1.1) Make sure the folder where index.html is owned by www-data (apache)

    chown -R www-data:www-data /path/to/webserver/www/project-arbitrage && chmod -R g+rw /path/to/webserver/www/project-arbitrage

2.1.2) Access the /project-arbitrage directory in your web browser

#### LOCAL MACHINE

2.2.1) Open terminal
2.2.2) Go to the folder where you have the index.html file
2.2.3) Start Python http server: 

    python -m SimpleHTTPServer 8000

2.4) Open your browser and go to http://127.0.0.1/8000
  
