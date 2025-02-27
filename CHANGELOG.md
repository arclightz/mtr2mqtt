# Changelog

<!--next-version-placeholder-->

## v0.5.0 (2021-09-25)
### Feature
* Add support to DPR990 and DPR991 receivers ([`acbbc51`](https://github.com/tvallas/mtr2mqtt/commit/acbbc516ce5b16321a3c2cd89eb253047a6bf30a))

### Fix
* Define encoding when opening metadata file ([`52f6812`](https://github.com/tvallas/mtr2mqtt/commit/52f6812d9af520db932bcdae9d5574a621eb7e19))

## v0.4.1 (2021-04-15)
### Fix
* Implement better mqtt connection handling, logging and reconnection logic ([`747fe05`](https://github.com/tvallas/mtr2mqtt/commit/747fe058027ede1b016bb0c9717a2d040b05caa1))

## v0.4.0 (2021-04-09)
### Feature
* **cli:** Add support for checking the software version ([`dc94b1c`](https://github.com/tvallas/mtr2mqtt/commit/dc94b1c6dfb8ddadd6f52cbfd1794eae725ede00))

## v0.3.2 (2021-04-02)
### Fix
* Change metadata file ([`2e976f9`](https://github.com/tvallas/mtr2mqtt/commit/2e976f9e5eb1f1da84bb9c9c3c96229b47eab5a7))

## v0.3.1 (2021-04-02)
### Fix
* Fix syntax in docker-compose file ([`e6204f5`](https://github.com/tvallas/mtr2mqtt/commit/e6204f5835fa04f8d5f0baae871a5be6ff23670b))

## v0.3.0 (2021-04-02)
### Feature
* Add docker-compose file and a sample metadata file ([`39d6ba7`](https://github.com/tvallas/mtr2mqtt/commit/39d6ba7c373ccf9b57f9577b76a3142ec20d70cd))

## v0.2.1 (2021-04-02)
### Fix
* Update dependecies for CVE-2020-29651 ([`926c24f`](https://github.com/tvallas/mtr2mqtt/commit/926c24f97ac60e96588c92c764ebd90d6159328a))

## v0.2.0 (2021-03-31)
### Feature
* **cli:** Add option to configure application using environment variables instead of cli arguments ([`5d6f94c`](https://github.com/tvallas/mtr2mqtt/commit/5d6f94cd9220415b2eb6903bbf89efaef0f21724))

## v0.1.2 (2021-03-28)
### Fix
* Add missing dependency to PyYAML ([`c6ea963`](https://github.com/tvallas/mtr2mqtt/commit/c6ea9634df7ccae78b8a44607ae7f7e4d70e89b1))

## v0.1.1 (2021-03-28)
### Fix
* Test semantic versioning ([`ad0814b`](https://github.com/tvallas/mtr2mqtt/commit/ad0814b2d84cd5678ef7b7199af57d9ea7c1959e))

## v0.1.0 (2021-03-28)
### Feature
* Add debug logging of unsupported packages ([`f7ae1e3`](https://github.com/tvallas/mtr2mqtt/commit/f7ae1e341a66cfff0689cd74fac474956c2f6e58))
* **mtr:** Add UTC timestamp field to reading output json ([`78fc3ff`](https://github.com/tvallas/mtr2mqtt/commit/78fc3ff4bebafe34e4a2f4ca2f11348c851944ff))
* **calibration support:** Add simple support for Utility packets having calibration date ([`950b731`](https://github.com/tvallas/mtr2mqtt/commit/950b73125ca46232766f36c9aa3304cacced16b6))
* **mtr2mqtt:** Initial commit ([`12dd367`](https://github.com/tvallas/mtr2mqtt/commit/12dd3673384d1bba466d437b72a6341be54fdcd2))

### Fix
* Ignore responses with checksum error ([`a6dd3c1`](https://github.com/tvallas/mtr2mqtt/commit/a6dd3c15ec1987fb84d7dc42cefea866e8a91a89))
* Fix utility packet return value to valid response instead of None if device wasn't calibrated ([`f5c7c09`](https://github.com/tvallas/mtr2mqtt/commit/f5c7c097ec78ac505841bbabd0040e189fed030c))
* **gitignore:** Fix typo in sample metadata file name ([`1b3125f`](https://github.com/tvallas/mtr2mqtt/commit/1b3125f45ce0a63cfd708c65797ecadba6c8fda4))
* **metadata:** Fix transmitter id comparison ([`4958340`](https://github.com/tvallas/mtr2mqtt/commit/49583404144c47f14e0ee2408a721752b78aafe0))

### Documentation
* Fix syntax in readme ([`0415bd5`](https://github.com/tvallas/mtr2mqtt/commit/0415bd5adc0e593d62d1ef4c1cf199b326ad4a2a))

### Performance
* Cut the execution tree and at the first supported device ([`077b551`](https://github.com/tvallas/mtr2mqtt/commit/077b5511174b67788814cc22fed6613eee522c67))
