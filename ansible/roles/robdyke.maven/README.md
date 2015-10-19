# ansible-maven

Install Maven in latest version from upstream.

# Role variables

- maven_version_major
  - Default: 3

- maven_version_minor
  - Default: 3

- maven_version_patch
  - Default: 3

- maven_mirror
  - Configure the mirror to download Maven.
  - Default: http://mirror.ox.ac.uk/sites/rsync.apache.org/maven

- maven_redis_shad256sum
  - SHA256 sum for the downloaded Maven redistributable package.
  - Default: 3a8dc4a12ab9f3607a1a2097bbab0150c947ad6719d8f1bb6d5b47d0fb0c4779

- maven_bin_path
  - Directory where to symlink the mvn binary to.
  - Default: /usr/local/bin

# Dependencies

None.

# License

Apache Version 2.0


# Author

Revised by Rob Dyke @robdykedotcom opengpsoc.org
Forked / Cloned from original work by Mark Kusch @mark.kusch silpion.de


<!-- vim: set ts=4 sw=4 et nofen: -->
