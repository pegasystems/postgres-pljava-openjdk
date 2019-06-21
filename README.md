# postgres-pljava-openjdk

DEPRECATED: the package 'oracle-java8-installer' is no longer available in any repos thus making this image ...very hard... to build.


Based on the image [xxBedy/postgres-pljava](https://github.com/xxBedy/postgres-pljava) but using openjdk as oracle jdk is not redistributable without first accepting the end-user license.

Furthermore, this image has been optimized to be as small as possible. The aforementioned image this was based on currently sits at 1.4GB. This image, after the various optimizations made (we're not squashing), is just shy of 450MB.

Image can be found here: [cdancy/postgres-pljava-openjdk](https://hub.docker.com/r/cdancy/postgres-pljava-openjdk/)
