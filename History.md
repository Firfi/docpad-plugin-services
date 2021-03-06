## History

- v2.2.6 May 30, 2013
	- Can now disable the facebook buttons by setting their `applicationId` property to `false`

- v2.2.5 May 30, 2013
	- Fix facebook like button on home page
	- Mild performance improvement
	- Updated for latest DocPad conventions

- v2.2.4 March 15, 2013
	- Added the ability to specify which social buttons you want outputted on the `getSocialButtons` method

- v2.2.3 March 7, 2013
	- Repackaged

- v2.2.2 February 11, 2013
	- Like/submit urls are now clean
	- Added support for:
		- Reddit Submit Button
		- Hacker News Submit Button

- v2.2.1 February 10, 2013
	- Fixed break when Quora follow button is not configured

- v2.2.0 February 10, 2013
	- Added support for:
		- Google Plus One Button
		- Facebook Like Button
		- Facebook Follow Button
		- Twitter Tweet Button
		- Twitter Follow Button
		- Github Follow Button
		- Quora Follow Button

- v2.1.0 February 3, 2013
	- Added support for [Disqus](http://disqus.com/) via `@getDisqus()` template helper
	- Added template helpers for all supported services
	- Fixed reinvigorate service not injecting when socket.io is used

- v2.0.0 December 29, 2012
	- Initital working release