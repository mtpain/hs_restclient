# 1.2.2 - 4/7/2016
  - Fix bug where getResourceList() would fail after the first page of results
    when using HTTPS connections.

# 1.2.1 - 3/1/2016
  - Add getResourceFileList (/hsapi/resource/\<pid\>/file_list/)
  - Add getUserInfo (/hsapi/userInfo/)
  - Add getScienceMetadata (/hsapi/scimeta/\<pid\>/)

# 1.2.0 - 12/2/2015
  - Add support for OAuth 2.0 authentication/authorization

# 1.1.0 - 6/12/2015
  - Add ability to supply user-defined upload progress callback functions to
    createResource() and addResourceFile().

# 1.0.0 - 6/2/2015
  - First release of HydroShare REST API Python client library
