```
async function fetchPools(chainId, dexName) {
return request(
    "GET",
    "https://api.covalenthq.com/v1/${chainId}/xy=k/${dexName}/pools/?quote-currency=USD&format=JSON&key=${API_KEY}"
  );
} 	
```


click below to see the code
