
<img alt="lbry-search-node-js" src="https://spee.ch/0/lbry-search-node-js.png" />

# lbry_search_nodejs
**Searches LBRY using lbrynet command and saves results to a text file.**

Using the bash shell script, `lbrynet claim search --text=<search term>`
this script searches LBRY and saves the results to a file. The save file is the same name as the search term. Do not use spaces use _ between words. Example: red_herring.<br/>

For installation just run:

git clone https://github.com/JupyterJones/lbry_search_nodejs.git<br/>
cd lbry_search_nodejs<br/>
Then ` npm install`<br/>
USE: `node lbry_search.js`<br/>do
<pre>
lbry_search_nodejs$ node lbry_search.js
this results in `Search for what ? `
## example:
    $ node lbry_search.js
     Search for what ? Red_Herring
    Search for: Red_Herring!

    The search results are in: Red_Herring.txt

        "page": 1,
        "page_size": 20,
        "total_items": 22,
       "total_pages": 2
      }

"page" 1,   &nbsp;&nbsp;&nbsp;&nbsp;  Indicates this is the first page.<br/>
"page_size": 20,  &nbsp;&nbsp;&nbsp;&nbsp;  shows 20 items are on this page.<br />
"total_items": 22, A total of 22 items were found'

excerpt from Red_Herring.txt:<br />
	
	{
	  "blocked": {
	    "channels": [],
	    "total": 0
	  },
	  "items": [
	    {
	      "address": "bFVQwDw8Dc2RLYo1W1vdfm41aUJYDmMp16",
	      "amount": "0.0005",
	      "canonical_url": "lbry://@TheAudiopedia#56/What-is-RED-HERRING-PROSPECTUS#0",
	      "claim_id": "0349ef66e89c8f9121d3481c08b1058c1e30a776",
	      "claim_op": "create",
	      "confirmations": 15594,
	      "height": 702164,
	      "is_channel_signature_valid": true,
	      "meta": {
	        "activation_height": 702164,
	        "creation_height": 702164,
	        "creation_timestamp": 1579475201,
	        "effective_amount": "0.0005",
	        "expiration_height": 2804564,
	        "is_controlling": true,
	        "reposted": 0,
	        "support_amount": "0.0",
	        "take_over_height": 702164,
	        "trending_global": 0.0,
	        "trending_group": 0,
	        "trending_local": 0.0,
	        "trending_mixed": 0.0
	      },
	      "name": "What-is-RED-HERRING-PROSPECTUS",
	      "normalized_name": "what-is-red-herring-prospectus",
	

</pre>


