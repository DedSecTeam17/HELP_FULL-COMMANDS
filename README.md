#FLUTTER 

1-intl transilation

Command to generate ARB file

``flutter pub pub run intl_translation:extract_to_arb --output-dir=<output directory> <localization file path>``

Sample:
``flutter pub pub run intl_translation:extract_to_arb --output-dir=lib/l10n lib\locale\locales.dart``


Command to Generate the Dart Files

``flutter pub pub run intl_translation:generate_from_arb --output-dir=<output directory> --no-use-deferred-loading <.arb files> <localization file path>``

Sample:
``flutter pub pub run intl_translation:generate_from_arb --output-dir=lib/l10n --no-use-deferred-loading  lib/l10n/intl_en.arb lib/l10n/intl_messages.arb lib/l10n/intl_ar.arb lib\localizations.dart``
