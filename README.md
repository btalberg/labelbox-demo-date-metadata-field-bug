# Demo a datetime bug in Labelbox

## Test

1. Copy `.env.template` to `.env`.
2. Set `LABELBOX_API_KEY`
3. Install packages: `poetry install`
4. Create ipython kernel:
   
```
poetry run ipython kernel install --name "labelbox-demo-date-metadata-field-bug" --user`
```

6. Run notebook!