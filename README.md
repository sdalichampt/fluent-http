## TODO

 + Supporter les coffee et less pré-générés
 + Supporter les templates pré-générés
 + Javadoc
 + handle logs properly rather than 'sysouting' like a pig ;)
 + PROD_MODE is not really convenient. It forces to have more complex prod script
 + Add some sort of http standard log
 + Cleanup Payload
 + Make Payload immutable?

# CI

[![Build Status](https://api.travis-ci.org/CodeStory/code-story-http.png)](https://api.travis-ci.org/CodeStory/code-story-http.png)

# Deploy on Maven Central

Build the release :

	mvn release:clean
	mvn release:prepare
	mvn release:perform

Go to https://oss.sonatype.org/, log in, go to **Staging Repositories**, close the *netcode-story-XXXX* repository then release it.
Synchro to Maven Central is done hourly.

