# 0.8.3

See https://github.com/svenfuchs/i18n/releases/tag/v0.8.3

# 0.8.2

See https://github.com/svenfuchs/i18n/releases/tag/v0.8.2

# 0.8.1

See https://github.com/svenfuchs/i18n/releases/tag/v0.8.1

# 0.8.0

See https://github.com/svenfuchs/i18n/releases/tag/v0.8.0

# 0.7.0

* Drop support to Ruby 1.8.7 / REE
* Drop support to Rails 2.3 / 3.0 / 3.1
* Remove deprecated stuff:
  - Setting `:default_exception_hander` Symbol to `I18n.exception_handler`.
  - `normalize_translation_keys` in favor of `normalize_keys`.
  - `:rescue_format` option on the exception handler.
  - `enforce_available_locales` now defaults to true with no deprecation message.
