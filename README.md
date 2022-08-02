
<!-- GETTING STARTED -->
## Getting Started

This is simple meta tag scrapper for search results.

<!-- Installation -->
### Installation

    composer require Muazzamkhan95/SearchEngineScrapping
    
    
    
## Usage

```
$client = new SearchEngine();


//Set Search Engine eg. google.com,google.ae,google.sa.....
$client->setEngine('https://www.google.ae');

//return array with keywords and position
$result = $client->search(['hello','car services']);

print_r($result);


```
