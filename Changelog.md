# Rest Framework Generic Relations Changelog

## v1.1.0

* Add `GenericModelSerializer` as a counterpart to `GenericRelatedField`.
* Dynamically determine the best serializer to use to serialize a model instance.
* Rename `determine_serializer_for_data` to `get_deserializer_for_data`
* Rename `determine_deserializer_for_data` to `get_serializer_for_instance`

## v1.0.0

* Add support for Django 1.8 and 1.9
* Add support for Django Rest Framework 3
* Drop support for earlier versions of Django and DRF

## v0.1.0

* Initial release
