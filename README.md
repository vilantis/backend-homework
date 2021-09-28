# URL shortener

Implement a URL shortening service using Django in compliance with the requirements below. Use any additional software necessary. DO NOT use any 3rd-party URL shortening services, APIs, or libraries. Format your code according to the PEP8 recommendations (maximum line length is up to you). Document the options you've considered, their trade-offs, and your decisions in the Readme file. Upload your solution to a repo on GitHub. If it's a public repo - just send us the link. If it's a private - invite user [antanas](https://github.com/antanas).

Completing all of the [required] requirements is necessary for passing the test. Satisfying [optional] requirements gives bonus points. Feel free to come up with and implement your own ideas in addition to, or instead of, the [optional] requirements.

While working on this assignment, you are welcome to have fun and over-engineer the hell out of it if you'd like and show off your strengths. If frontend is not your thing, feel free to keep the user interface minimal. We’ll be mostly focusing on backend solution.

## Requirements
### Required 
- [ ] On the main page of the service, provide a web interface by which a user can shorten a URL;
- [ ] If a user visits the short URL, they must receive a temporary HTTP redirect to the long URL;
- [ ] Attempt to optimize the speed at which the URL is resolved to the best of your ability;
- [ ] All the short URLs must be reasonably short and of the same length;
- [ ] Given a short URL, it must be impossible to identify the long URL, when the short URL was generated, or which user generated it, or any other metadata in any other way than via the service API;
- [ ] It must be impossible to easily identify which of the two given short URLs was generated earlier;
- [ ] If the same long URL is shortened the second time, it must produce a different short URL;
- [ ] Provide a Readme file with instructions on how to run the service;
- [ ] Provide tests covering the core functionality;

### Optional 
- [ ] Provide an admin interface for the user which allows to deactivate or permanently delete any of the URLs they have shortened;
- [ ] Record the click statistics for each short URLs that the user has created and display it in the admin interface: time; IP address; HTTP Referer;
- [ ] Expiration time: automatically deactivate the URL at a given time (configured per URL in the admin interface);
- [ ] Limit maximum number of clicks on URL: automatically deactivate the URL after the limit is reached;
- [ ] Allow to run the service with docker-compose up command;
- [ ] Provide a benchmark to showcase the speed of redirecting from short to long URLs.
