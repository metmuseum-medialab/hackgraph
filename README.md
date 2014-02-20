hackgraph
=========

A force-directed graph of hackpad pages. Using arbor for teh graph physics, and hackpads node api

to get it running on  your server:

- have node installed
- clone this repo.
- copy secrest.tpl.js to secrets.js
- fill out secrets.js with:
-- your hackgraph API key,  
-- name of your space, eg [hackpad_name].hackpad.com. the thing in brackets is your hackpad_name
-- port you want the server to run on (prod_port is something I think helps if you want to run in different environments, ymmv. I just make them both the same)
- run the server
- feel the magic.


this is way beta, use at your own risk.

all the credit to the guys who make arbor js : http://arborjs.org/ and the guys that make the hackpad API.
