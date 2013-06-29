SuperGlue
=========

'Web 2.0' promised that everyone could become a media publisher, but had exactly the opposite result: Today, most people's web content is locked into the proprietary services of only a handful of Internet social media giants. The early Web culture of self-made and self-hosted homepages has almost disappeared.

A major reason for this is that corporate social media systems were much easier to use than classical homepages. Users no longer need to administer servers or upload HTML files. With SuperGlue, we are developing a system that gives back everyone their truly own website. For this purpose, we build on our existing 'HotGlue' (https://github.com/hotglue/hotglue2) web application - which makes the creation of web sites as easy as the use of basic text and painting programs -, but improve it so that it no longer needs to run on a central server.

Usual CMS (Content Management Systems) pose rather heavy requirements onto the hosting platform they are deployed at. For example Wordpress needs a database (MySQL), server-side parser (PHP) and a serious HTTP server such as Apache. Additionally, all of the web-content is processed on every request (or less often if caching proxy/accelerator is used), which requires a fair bit of processing power for every page hit.

Naturally no one would like the idea of keeping a noisy, rattling 19-inch rack server in a living room. SuperGlue provides an alternative for that – it divides the process of dynamic content manipulation into two separate tasks, each executed on a platform the best suitable for it. Power-hungry processing of user interactions is done in a Web-browser running on user's laptop and storage of resulting data happens on a tiny Web-server installed on user's desk (or elsewhere).

Such a model allows to re-purpose available computational resources of personal computers and by that significantly simplify hosting requirements. Now the server does not need to grind through databases and interpret scripts – all data is already stored in pre-processed state, ready to be served as-is. This kind of 'static' (citing Jaromil “baked, not fried”) content requires very little processing power from the server and thus this server can become a miniature wall-plug, producing zero-noise and consuming very little electrical energy.

Since the miniature server can be easily kept at home the user can skip the middle-man services and uncompromisingly own the data.


