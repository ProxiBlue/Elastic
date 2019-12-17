# Elastic

Simple module to change smile elsaticsearch index behaviour

The default behaviour of elastic search is to split words on non alpha numeric parts.

Example HBO-OOP becomes two search terms HBO and OOP

This is not always desired (example specific SKU's), so all this does is to remove that behaviour, and set SKU 
and Description attributes to also use 'whitespace' only as word boundry



