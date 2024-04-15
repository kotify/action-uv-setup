# Github Action to setup uv

### Example

```yaml
jobs:
  build:
    steps:
      - uses: actions/checkout@v4
      - uses: kotify/action-uv-setup@v1
        with:
          path: backend/requirements.txt
          python-version: '3.11'
          uv-version: '0.1.24'
```
