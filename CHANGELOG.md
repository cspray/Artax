v2.0.2
------

- Include fixes from pull requests #78 and #87

v2.0.1
------

- Remove cyclic reference involving RequestCycle and thus the socket resource, which led to the socket only being freed after cycle collector kicked in.
- Complete Notify::RESPONSE with an export_socket function.
- Fixed issue #71 (see 7b9be105)

v2.0.0
------

- Updated amp dependency to version ^1