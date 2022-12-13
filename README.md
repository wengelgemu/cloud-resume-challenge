# cloud-resume-challenge
My educational journey at Loyola Marymount University didn’t always start with the Information Systems and Business Analytics major. In the fall of 2019, I was initially enrolled in Computer Science, where classes were intently focused on learning different programming languages for creative manipulation. The most important projects tested our creativity and skill with the tools and functions we were taught, the output oftentimes looking like games or computational codes. While I loved the educational experience, I always felt that something was lacking for me. I couldn't envision ways I could apply what I had done in practical personal ways outside of playful projects or an official engineering position at work. I found more joy in the courses that involved UX/UI and website-related work (React, HTML and CSS) because I could see the difference I could make with these tools now. I understood creating with accessibility and human interaction in mind, and I loved the ability to use and share with others something like a completed web project. The Cloud Resume Challenge felt like the perfect successor to this sentiment, allowing me to learn new tools that are real and used by the industry as much as they can be for myself. The sharability and portfolio-building aspect of it all gave it a dual purpose and motivated me even further to finish. 

The beginning and end of my Cloud knowledge revolved around Google drive and its application suite. I understood that content could be hosted but I imagined it was virtually unlimited, like magic or something, and that upgrades or additional payments were a scam. Every time my iPhone library stopped syncing to the cloud id mutter something along the lines of “How am I out of cloud storage? It is invisible and virtually up in the air, just make more room?”. This class truly put into perspective the amount of energy and power running what creates a seemingly endlessly expanding cloud. Between visiting the physical backend in University Hall and seeing the usage statistics right in front of me in AWS cost explorer and Elastic Compute Cloud, I feel like I've watched the curtain drop right in front of me. 

Interacting with Amazon Web Services has been an invigorating experience because everything is laid out in front of you so directly and conveniently. After the learning curve that is getting familiar with these technologies, it has become a lot easier to separate functional services to their advantages. One of the services I spent the most time with was S3 (Simple Storage Service), as it reminded me most of the way standard computer folders looked I was able to easily organize and update my website according to the buckets laid within “wengel.site”. This is where the site truly lived, encapsulating all the HTML and CSS files as well as any other assets (scripts, images, and fonts) that exist on the page.

When it came to more interactive aspects like keeping a running visitor counter I was required to flesh out a backend using the javascript given in class and a python code. When it comes to creating functions that work seamlessly with the rest of the site properties, Amazon Web Services has tools such as Lambda. All these services remind me of a tag team in a way because Lambda reaches back to another service called the API Gateway. Here I created an API called visitorCount which is deployed and then invoked by Lambda; the Lambda function updates the visitorCount table (brought in by the DynamoDB NoSQL database) by incrementing the item by 1 every time my resume is accessed.

What I loved about this project was that everything was so new to me, making it an experimental and educational project. There was one feature I had encountered before and that was purchasing a domain from Name Cheap! I had the site wengel.me purchased for my portfolio but had only applied it to services such as Webflow in the past, which does all the nitty-gritty of connecting the page for you. In this project I was able to do this myself with Route 53’s domain registration where I hosted a public zone for my site, creating several different records to route traffic to the right destination. This, paired with AWS Certificate Manager created CNAMEs that brought wengel.site and www.wengel.site secured under HTTPS together.

Although this project was largely independent and followed alongside your instruction, in a funny way it felt like a wholly collective effort working hand in hand with all of the microservices. They all interact with one another in distinct ways that make such a complex process very digestible for me. If I had to pinpoint a place where I struggled the most it would be at times feeling overwhelmed by the sheer number of services I could point to in case something went awry. Debugging and finding the source of error could get pretty intensive if you’re not running small incremental tests along the way. Testing little by little, as well as making sure one's files are organized is the best advice I could give someone in my place.
