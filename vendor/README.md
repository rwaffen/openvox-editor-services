# Vendored Gems

The OpenVox Puppet DSL server is designed to run within the OpenVox Agent Ruby environment, which means no access to native extensions or Gem bundling.

This means any Gems required outside of the OpenVox runtime for the language server must be vendored in this directory and the load path modified in the `openvox-languageserver` file.

Note - To comply with Licensing, the Gem source should be MIT licensed or even more unrestricted.

Note - To improve the packaging size, test files etc. were stripped from the Gems prior to committing.

Gem List
--------

* voxpupuli-puppet-lint-plugins (metadata dependency version 7.0.0)
* hiera-eyaml (https://github.com/voxpupuli/hiera-eyaml ref v2.1.0)
* puppetfile-resolver (https://github.com/puppetlabs/puppetfile-resolver.git ref v0.6.3)
* molinillo (https://github.com/CocoaPods/Molinillo.git ref 0.6.6)
* openvox-strings (https://github.com/voxpupuli/openvox-strings.git ref v7.1.0)
* rgen (https://github.com/mthiede/rgen.git ref v0.10.2)
* yard (https://github.com/lsegal/yard.git ref v0.9.24)
* puppet-lint (RubyGems version 5.1.1)
* puppet-lint-absolute_classname-check (RubyGems version 5.0.0)
* puppet-lint-anchor-check (RubyGems version 3.0.0)
* puppet-lint-exec_idempotency-check (RubyGems version 2.0.0)
* puppet-lint-file_ensure-check (RubyGems version 3.0.0)
* puppet-lint-leading_zero-check (RubyGems version 3.0.0)
* puppet-lint-lookup_in_parameter-check (RubyGems version 3.0.0)
* puppet-lint-manifest_whitespace-check (RubyGems version 2.0.0)
* puppet-lint-optional_default-check (RubyGems version 3.0.0)
* puppet-lint-package_ensure-check (RubyGems version 0.2.0)
* puppet-lint-param-docs (RubyGems version 3.0.0)
* puppet-lint-param-types (RubyGems version 3.0.0)
* puppet-lint-params_empty_string-check (RubyGems version 3.0.0)
* puppet-lint-params_not_optional_with_undef-check (RubyGems version 1.0.0)
* puppet-lint-resource_reference_syntax (RubyGems version 3.0.0)
* puppet-lint-strict_indent-check (RubyGems version 5.0.0)
* puppet-lint-topscope-variable-check (RubyGems version 3.0.0)
* puppet-lint-trailing_comma-check (RubyGems version 3.0.1)
* puppet-lint-unquoted_string-check (RubyGems version 4.1.0)
* puppet-lint-variable_contains_upcase (RubyGems version 3.0.0)
* puppet-lint-version_comparison-check (RubyGems version 3.0.0)
