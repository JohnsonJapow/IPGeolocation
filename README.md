The external IP-API.com:

    https://ip-api.com/docs/api:json
    
    integrating the functionality to retrieve information involves sending an IP request to the API. You have the flexibility to choose the language,
    
    specify the information field, and designate a callback, which can then be added to the URL.

#Customized IP field to get the response from the API
    
    To tailor the IP field for a targeted response from the API, navigate to the return data section on the website. 
    
    There, a numeric value generated by the website will help fetch a specific combination of IP information fields.

#Usage limit
    
    When utilizing the free version, be aware of the X-Rl and X-Ttl values in the response HTTP header. 
    
    X-Rl indicates the remaining number of requests within the current rate limit window, while X-Ttl denotes the time in seconds until the limit is reset. 
    
    Always ensure that your implementation checks the X-Rl header's value, and if it reaches 0, refrain from sending further requests for the duration specified by X-Ttl in seconds.