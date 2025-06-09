# Zhenyu Jiang + Nick Nguyen
How are graceful degradation and service workers related?
- They are related because the graceful degradation provides a fallback for your website say when browser doesn't support a fancy css component, then you can still display something that still looks acceptable to the user and not crashing the site.
- Service workers apply same logic, but at the network level . For example, I cached the website html, css, and js of a website, and when the user access my site with bad wifi or no network connection at all, I can still display the website properly to them from the cache and if they try to make some request on the website that requires data that isn't cached, I can then show them the custom "you are offline" html instead of a 404 error.

Github page:
https://xdawn66.github.io/Cse110-Lab8/
