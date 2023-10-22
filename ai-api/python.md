# Python

## Using requests

```python
import requests
data = {'input': 'Hello!'}
response = requests.post('https://api.slxuniverse.xyz/ai', json=data)
print(response.json())
```
