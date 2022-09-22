# interlok-base-filesystem

[![GitHub tag](https://img.shields.io/github/tag/adaptris/interlok-base-filesystem.svg)](https://github.com/adaptris/interlok-base-filesystem/tags)
[![license](https://img.shields.io/github/license/adaptris/interlok-base-filesystem.svg)](https://github.com/adaptris/interlok-base-filesystem/blob/develop/LICENSE)
[![Actions Status](https://github.com/adaptris/interlok-base-filesystem/actions/workflows/zip-and-publish.yml/badge.svg)](https://github.com/adaptris/interlok-base-filesystem/actions)

The base directory structure used in an Interlok installation:
 - bin
  - README.TXT: Text file explaining how to use the start scripts
  - start-interlok: Bash script to start Interlok on Linux/Mac
  - start-interlok.bat: Bat script to start Interlok on Windows
 - config
  - adapter.xml: Adapter XML configuration
  - bootstrap.properties: Adapter bootstrap properties
  - log4j2.xml: Log4j XML configuration
 - webapp
  - ROOT.war: The base webapp started when Jetty management component is used.
