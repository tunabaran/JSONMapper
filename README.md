# JSONMapper
Mapper class for JSON.

JSONMapper is a library designed to simplify creating Java object from JSONs and creating JSON from java objects.

# HOW TO USE

You can access methods from Class reference.

**You can get Java object from json with :** 

```

User user = JsonMapper.getObjectFromJson(json,User.class);

```

**And you can get JSONObject form java object with :**

```

JSONObject jsonObject = JsonMapper.getJsonObject(user);

```

# License

Copyright (C) 2018

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

