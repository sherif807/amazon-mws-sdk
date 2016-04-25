Amazon MWS API Installation
========================

Into a symfony2 project
-----------------------

Add the reference into your composer.json : 

    "sherif807/amazon-mws-sdk": "dev-master"

Use in controller :

     $client = new \MwsSearchClient(/* args */);
