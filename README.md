E.164 Telephone Number Type
===========================

WARNING: This is an **ALPHA** release. Do *not* run this software in production.

E.164 is a recommendation by the International Telecommunication Union (ITU) for
international telephone numbers. The E164 type provides a convenient method of
storing international telephone numbers consistent with the E.164 recommendation.

In particular,

* Country code validation
* Rudimentary format checking
	* Number consists of proper + prefix followed by digits.
	* Minimum and maximum length checking for corresponding E.164 Type

The E164 type does not check that the number is consistent with formats specific
to particular national standards: formats vary by country. (Support for national
format checking may be added in a future release.)
