CHANGELOG

#### 0.0.5: Sep 3, 2019
* Fix for https://github.com/postmanlabs/curl-to-postman/issues/1 - cURL commands with `$` prepended to arguments not importing correctly
* Fix for https://github.com/postmanlabs/curl-to-postman/issues/2 - the importer was using -X to determine method, not -d or --head
* Fix for https://github.com/postmanlabs/curl-to-postman/issues/4 - Data parameters are added to the URL if the method is determined to be GET, PUT, or HEAD

#### 0.0.4: June 5, 2019
* Updated dependency versions
* Updated lockfile for npm@6.4.1

#### 0.0.3: May 29, 2019
* First public (beta) release
* Conforming to the internal Postman plugin interface
* Fixes for Github issues - 4770,3623,3135,4018,5737,5286, among others