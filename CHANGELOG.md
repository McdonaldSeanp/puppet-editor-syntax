# Change Log

All notable changes to the "puppet-editor-syntax" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## Unreleased

## [1.3.0] - 2018-11-29

### Fixed
- ([GH-22](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/22)) Fix broken heredoc string highlighting

## [1.2.0] - 2018-11-27

### Fixed
- ([GH-16](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/16)) Fix broken variable and interpolated string highlighting

## [1.1.0] - 2018-10-30

### Added
- ([GH-8](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/8)) Add regex support
- ([GH-4](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/4)) Allow numbers in Datatype

### Fixed
- ([GH-6](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/6)) Correctly tokenize chaining arrows

## [1.0.0] - 2018-06-12

### Added
- Update syntax with atom language CSON
- Add syntax highlighting for number literals
- Add syntax highlighting for plans
- Add Puppet Data Types to syntax highlighting

### Fixed
- ([GH-1](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/1)) Fix inherits keyword matching
- ([GH-2](https://github.com/lingua-pupuli/puppet-editor-syntax/issues/2)) Properly parse comments in multi-line arrays

## [0.0.1] - 2018-02-19

- Initial Puppet Syntax file from the [Puppet VSCode Extension v0.4.0](https://github.com/lingua-pupuli/puppet-vscode/blob/8da164b2ce9630ad2b8a2137fed8f4ae0f46a1c3/client/syntaxes/puppet.tmLanguage)
