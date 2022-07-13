# Requests maken in verschillende talen

### Python

```python
## Dit heeft een pakket van PIP nodig: pip install requests

import requests

r = requests.get(url = "https://itsfinniii.com/api/sd2b/endpoints.json")    # Raw request
rjson = r.json()    # JSON data
rstatuscode = r.status_code    # Status Code
```
