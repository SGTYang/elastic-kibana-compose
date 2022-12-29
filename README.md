# elastcisearch index mapping(schema)
```
PUT /${index_name}
{
  "mappings": {
    "properties": {
      "usage": {
        "type": "keyword"
      },
      "image_class": {
        "type": "keyword"
      },
      "data_source": {
        "type": "keyword"
      },
      "file_path": {
        "type": "text"
      }
    }
  }
}
```