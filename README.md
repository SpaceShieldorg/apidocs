# apidocs

```
codes
200 = Ok
400 = Bad Request
401 = Invalid auth token/died
403 = Forbidden
404 = Not Found
405 = lack of access
```

<h2>Example hello world</h2>

```python
import requests
import json
response = requests.get('https://api.spaceshield.org/helloworld', headers={'Authorization': 'Your-token'})
print(response.status_code)
print(response.text)
```
<h2>banking</h2>
<h2>get information from oauth2</h2>
