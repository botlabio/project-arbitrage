# project-arbitrage

WHAT: A data visualization protect to identify traffic flows associated with the largest arbitrage sites in the world. 
DATA: Ad exchange data aggregated from multiple ad exchange
TIME: Early July 2015

### Background

In July 2015 there were multiple websites with very low Alexa Traffic Ranks sent collectively ten billion or more invalid impressions to ad exchanges every day. These impression events were very easy to identify as invalid through simple logfile analysis. Since then traffic profiles of some of these sites, for example likes.com, have improved significantly and is now far harder to confirm as invalid. More than any other traffic source, the IP ranges 173.209.211/24 and 173.209.212/24 had a very strong affinity with these sites. 

Going through 1-2 minutes of 'getting started' as outlined below, you'll have access to a tree visualization showing 50 of the largest sites that related to 173 and other poor quality traffic sources, and how different IP's contributed traffic to those sites. Further you can see for each IP's how it contributed traffic to different sites. 

With one click access additional information on IP or domain from: 

- Robtext
- TCPutils
- Myip
- Sans
- Blacklist checker (checks ~100 blacklists)
- w3bin
- Whoisology

### Usage

You can click through any node (circle) and for domain and IP nodes you right click to access the external sources. 

### Screenshot

[![Screen Shot 2016-09-08 at 12.25.19.png](https://s12.postimg.org/dvhujjoql/Screen_Shot_2016_09_08_at_12_25_19.png)](https://postimg.org/image/qa4mjvg8p/)

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
  
