# Firefox Add-on: Enterprise Policy Generator (WebExtension)

## Release Notes

### [Version 1.1.0](https://github.com/cadeyrn/enterprise-policy-generator/releases/tag/v1.1.0) (2018-05-27)

#### Enhancements

- **the downloads permission is no longer mandatory!** This means that the extension can now be used completely
  without any special permission. If you want to download the “policies.json” file, you can easily grant the
  permission at runtime, fixes [#5](https://github.com/cadeyrn/enterprise-policy-generator/issues/5)

#### Translations

- added Upper Sorbian translation (Thanks, milupo!)
- added Lower Sorbian translation (Thanks, milupo!)

#### Code Quality

- a lot of code refactoring to improve code maintainability and to make it easier for others to contribute to the
  code base, fixes [#8](https://github.com/cadeyrn/enterprise-policy-generator/issues/8)

#### Dependencies

- updated eslint-plugin-compat from version 2.2.0 to 2.3.0
- updated eslint-plugin-no-unsanitized from version 3.0.1 to 3.0.2
- updated web-ext from version 2.6.0 to 2.7.0

[All Changes](https://github.com/cadeyrn/enterprise-policy-generator/compare/v1.0.1...v1.1.0)<br />
[Download Signed WebExtension](https://addons.mozilla.org/en-US/firefox/addon/enterprise-policy-generator/versions/?page=1#version-1.1.0)

---

### [Version 1.0.1](https://github.com/cadeyrn/enterprise-policy-generator/releases/tag/v1.0.1) (2018-05-20)

#### Translations

- fixed typo in English translation

[All Changes](https://github.com/cadeyrn/enterprise-policy-generator/compare/v1.0.0...v1.0.1)<br />
[Download Signed WebExtension](https://addons.mozilla.org/en-US/firefox/addon/enterprise-policy-generator/versions/?page=1#version-1.0.1)

---

### [Version 1.0.0](https://github.com/cadeyrn/enterprise-policy-generator/releases/tag/v1.0.0) (2018-05-20)

- initial release for [addons.mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/enterprise-policy-generator/)

#### Features of the first version

- simply click together the desired Enterprise Policies
- supports all policies which are supported by Firefox 60
- validation for mandatory fields
- special marking of policies that only work with Firefox ESR
- info links for some policies to get additional information

[Download Signed WebExtension](https://addons.mozilla.org/en-US/firefox/addon/enterprise-policy-generator/versions/?page=1#version-1.0.0)
