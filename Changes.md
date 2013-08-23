---
layout: page
title: Changes
---

## 0.3.2 2013-08-23T13:21:54Z
### Minor
 - Bundle images in dist
 - Add Travis CI checking

## 0.3.1 2013-08-22T10:34:10Z
### Bug fixes
 - Accidentally left broken code with colored -> `_colored` transition

### Documentation
 - Screenshot images added to all the themes.

## 0.3.0 2013-08-22T09:38:29Z
### !Major
 - Now supports custom color themes controllable on the CLI
 - Internals have `MetaPOD` coverage

### Dependencies::Added / runtime requires
 - `Module::Runtime`
 - Moo
 - `Role::Tiny`

### Documentation
 - `MetaPOD` annotations and graphs added.

## 0.2.0 2013-08-21T14:32:08Z
### !Major
 - New feature, shows aggregate of plugins that were not in any predefined phase.
 - Better docs on a few phases.

### Dependencies::Added / develop requires
 - `Test::Kwalitee` `1.08`

### Dependencies::Added / test requires
 - `Capture::Tiny`
 - blib

### Dependencies::Changed / build requires
 - `Module::Build` `0.4005` → `0.4007`

### Dependencies::Changed / configure requires
 - `Module::Build` `0.4005` → `0.4007`

### Dependencies::Changed / develop suggests
 - `Dist::Zilla::PluginBundle::Author::KENTNL` `v1.7.3` → `v1.8.0`

### Dependencies::Removed / test requires
 - `File::Find`
 - `File::Temp`

## 0.1.4 2013-05-17T12:45:25Z
### Dependencies::Added / develop requires
 - `Test::CPAN::Changes` `0.19`

### Dependencies::Changed / build requires
 - `Module::Build` `0.4003` → `0.4005`

### Dependencies::Changed / configure requires
 - `Module::Build` `0.4003` → `0.4005`

### Dependencies::Changed / develop suggests
 - `Dist::Zilla::PluginBundle::Author::KENTNL` `v1.7.0` → `v1.7.3`

### Documentation
 - Change hotlink image URI to a github-pages based one to be more friendly to githubs service.
 - https://github.com/blog/1482-
 - https://help.github.com/articles/using-submodules-with-pages

### Packaging
 - Utilise `test_requires`

## 0.1.3 2013-01-25T23:04:24Z
 - Bugfix release

### Bugs
 - Load `Term::ANSIColor` lazily to stop it being loaded when all the other commands are ( Thanks Oliver Mengué ).

### Dependencies::Added / develop requires
 - `Pod::Coverage::TrustPod`
 - `Test::CPAN::Meta`
 - `Test::Pod` `1.41`
 - `Test::Pod::Coverage` `1.08`
 - version `0.9901`

### Dependencies::Changed / build requires
 - `Module::Build` `0.3601` → `0.4003`

### Dependencies::Changed / configure requires
 - `Module::Build` `0.3601` → `0.4003`

### Dependencies::Changed / develop suggests
 - `Dist::Zilla::PluginBundle::Author::KENTNL` `v1.3.0` → `v1.7.0`

### Dependencies::Changed / test requires
 - `Test::More` `0.88` → `0.98`

### Documentation
 - Copyright = `2013`

### Meta
 - Bugtracker switched to github

### Tests
 - Regenerated 000-report-versions-tiny.t

## 0.1.2 2012-05-09T07:25:48Z
 - Maintenance Release.

### Dependencies::Added / runtime requires
 - perl `5.006`

### Dependencies::Changed / develop recommends
 - `Dist::Zilla::PluginBundle::Author::KENTNL::Lite` `0.01009803` → `v1.3.0`

### Dependencies::Changed / develop suggests
 - `Dist::Zilla::PluginBundle::Author::KENTNL` `v1.0.0` → `v1.3.0`

### Internals
 - add $AUTHORITY to all packages.

### Packaging
 - Update LICENSE ( Year, Indent, Address )
 - Export `x_authority` in Meta

### Tests
 - Add a minimum version release test

## 0.1.1 2011-09-02T09:37:14Z
### Dependencies::Added / runtime requires
 - strict
 - warnings

### Dependencies::Removed / test requires
 - English

### Documentation
 - Document how to turn off colouring ( thanks harleypig / ayoung / Alan Young )

### Metadata
 - Github Urls updated/corrected.

### Packaging
 - Author/Release tests now in xt/
 - Alan Young is now an author.

### Tests
 - compile test updated.

## 0.1.0 2011-07-14T06:13:32Z
 - First version.