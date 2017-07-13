# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.7.0] - 2017-04-26
- Change logic of the autoupdate wp

## [1.6.0] - 2017-04-26
-Add config to prevent autoupdate wordpress

## [1.5.0] - 2017-01-26
- Added logic for generating Wordpress config file for multisite installations

## [1.4.0] - 2016-11-04
- Removed magento-composer-installer dependency

## [1.3.0] - 2016-10-13
### Added
- Added generator for Wordpress config file
- Worpress generator leverage Twig template engine, that could be used for refactor even the Magento genertator

## [1.2.0] - 2016-10-11
### Added
- .env file is now optional, so environment vars can be pulled directly from the environment where the script is lauched
- <composer_vendor_path> in the local.xml can be set via environment variable
