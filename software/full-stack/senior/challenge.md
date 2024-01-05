### Objective

Your assignment is to implement a URL shortening application using Node and any framework.

### Brief

ShortLink is a URL shortening application where you enter a URL such as https://challenge.com/great and it returns a short URL such as http://short.est/GeAi9K.

### Tasks

- Implement backend assignment using:
    - Language: **Node**
    - Framework: **preferably Serverless or NestJS with an ORM** 
    - Three endpoints are required
        - /encode - Encodes a URL to a shortened URL
        - /decode - Decodes a shortened URL to its original URL.
        - /urls - Returns the list of shortened URLs
    - Both endpoints should return JSON
    - There is no restriction on how your encode/decode algorithm should work. You just need to make sure that a URL can be encoded to a short URL and the short URL can be decoded to the original URL.
    - Persist short URLs to a database.
    - Provide API tests for both endpoints

- Implement frontend assignment using:
    - Language: **JS/TS**
    - Framework: **ReactJS, TailwindUI**
    - should be able to submit the long url and display the shortened url
    - should be able to visit or copy the shortened url
    - should be able to type in the encoded url and get the decoded one
    - should be able to see a list of encoded urls

### Evaluation Criteria

- **Node** best practices
- **ReactJS** best practices

### Application Submit

Please organize, design, test and document your code. 

Provide detailed instructions on how to run your assignment in a separate markdown file

Push the code to a git repo and send the URL when done

All the best and happy coding,