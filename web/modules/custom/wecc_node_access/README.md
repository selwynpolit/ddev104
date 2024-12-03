# WECC Node Access

This custom module allows tagged content to be edited by users with the same tag.

## Installation
1. Add a taxonomy vocabulary called "WECC Edit Access" at /admin/structure/taxonomy/add
2. Add terms such as RIPA, Comms etc. representing the tags that will be used to grant edit access to content.
3. Add a multivalue field to the user entity called "field_wecc_edit_access" at /admin/config/people/accounts/fields. This field should be of type "Entity Reference" with the target type "Taxonomy term" and the target bundle "WECC Edit Access".
3. Add a field called "field_wecc_edit_access" of type "Entity Reference" with the target type "Taxonomy term" and the target bundle "WECC Edit Access".
4.
