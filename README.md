# Multi Search engine
The website tries to make internet searches more convenient and faster. Especially for users who find it easier to formulate a query in Czech but would like to have access to more results.

By entering search text in Czech, the user can search for results in Czech and English at once.

Typical scenario:
1. The user enters the search text in Czech.
2. the page searches:
    - Images (in English)
    - Links in the original language
    - Links in English

## Instalation
- Python 3.9
- Python packages:
    - flask
    - flask-restx
    - requests
    - deepl
    - imgurpython

## API used    
- Bing: https://docs.microsoft.com/en-us/rest/api/cognitiveservices-bingsearch/bing-web-api-v7-reference
- Imgur: https://api.imgur.com/
- DeepL: https://www.deepl.com/en/docs-api/
- xkcd: https://xkcd.com/json.html


## Questions  
What problem are you solving?
- Convinience of multilanguage searching

Why is your idea unique?
- It tries to make non-google services usable for tech-oriented persons

What are the steps to achieve your goals?
- Ideally get support from Microsoft

Your customers are students, how large is the target audience?
- Very specific audience in Czech Republic, but it could be extended by a lot with more languages support

Quantify benefits of your product (cheaper, faster, other product improvements) 
- Faster (and time is money)

Who are the competitors? Why are you better?
 - Google, but this service is more tailored to multilanguage search
 - Also DeepL might offer better translation support 

## Limitations/Future improvements
- All API have daily/months query limits
- Graphic should be updated (use bootstrap)
- English results could be automatically translated
- Add support for more languages


Swagger
http://nas.daxsoft.cz:5000

Web
http://nas.daxsoft.cz:5000/index
