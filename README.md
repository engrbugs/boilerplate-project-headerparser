# API Project: Request Header Parser Microservice for freeCodeCamp

## See this in action: [https://whoami-microservice-engrbugs.herokuapp.com/](https://whoami-microservice-engrbugs.herokuapp.com/)
<br>

[![Run on Repl.it](https://repl.it/badge/github/freeCodeCamp/boilerplate-project-headerparser)](https://repl.it/github/freeCodeCamp/boilerplate-project-headerparser)
### User stories:
1. I can get the IP address, preferred languages (from header `Accept-Language`) and system infos (from header `User-Agent`) for my device.

#### Example usage:
* [base_url]/api/whoami

#### Example output:
* `{"ipaddress":"159.20.14.100","language":"en-US,en;q=0.5","software":"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"}`