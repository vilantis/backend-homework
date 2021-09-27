# URL shortener

Implement a URL shortening service using Django in compliance with the requirements below. Use any additional software necessary. DO NOT use any 3rd-party URL shortening services, APIs or libraries. Format your code according to the PEP8 recommendations (you are free to choose your own favourite line length though). Document the options you've considered, their trade-offs and your decisions in the Readme file. Upload your solution to a repo on GitHub. If it's a public repo - just send us the link. If it's a private - invite user [antanas](https://github.com/antanas).

Implementation of all the [required] lines is necessary for passing the test. Implementation of [optional] lines gives bonus points. Feel free to come up with and implement your own ideas in addition to, or instead of, the [optional] requirements.

While working on this assignment, your are welcome to have fun and over-engineer the hell out of it if you like, and show off your strengths. If frontend is not your thing, keep the user interfaces minimal. We’ll be mostly focusing on backed solution. It’s for you to decide.

## Requirements
### Required 
- [ ] On the main page of the service, provide an web interface by which a user can shorten a URL;
- [ ] if a user visits the short URL, he/she must receive a temporary http redirect to the long URL in response;
- [ ] attempt to optimize the speed at which the URL is resolved to the best of your ability;
- [ ] all the short URLs must be of the same length, and reasonably short;
- [ ] given a short URL, it must be impossible to identify the long URL, or when the short URL was generated, or which user generated it, or any other metadata in any other way than via the service API;
- [ ] it must be impossible to easily identify which of the two given short URLs was generated earlier;
- [ ] if the same long URL is shortened the second time, it must produce a different short URL;
- [ ] Provide a Readme file with instructions how to run the service;
- [ ] Provide tests covering the core functionality;

### Optional 
- [ ] Provide an admin interface for the user which allows to deactivate or permanently delete any of the URLs they have shortened;
- [ ] Record the click statistics for each short URLs and display it in the admin interface to the short URL creator user: time;IP address; HTTP Referer;
- [ ] Expiration time: automatically deactivate the URL at a given time (configured per URL in the admin interface);
- [ ] Limit maximum number of clicks on URL: automatically deactivate after the limit is reached;
- [ ] Allow to run the service with docker-compose up command;
- [ ] Provide a benchmark to showcase the speed of redirecting from short to long URLs.
