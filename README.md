# apidocs

<h2>Example hello world</h2>
```no-highlight

import requests
import json
response = requests.get('https://api.spaceshield.org/helloworld', headers={'Authorization': 'Your-token'})
print(response.status_code)
print(response.text)
