# Morfologik (Polish) Analysis for Elasticsearch

Morfologik (Polish) Analysis plugin integrates Lucene Morfologik (polish) analysis module into elasticsearch.
Originally created by [monterail](https://github.com/monterail/elasticsearch-analysis-morfologik).

## Installation

Simply run at the root of your ElasticSearch according to the version you use (assuming zip file located at / directory):

- 2.4.1 

  ```bash
  $ bin/plugin install https://github.com/antqa/elasticsearch-analysis-morfologik/releases/download/2.4.1/elasticsearch-analysis-morfologik-2.4.1.zip
  ```

The plugin includes `morfologik` analyzer and `morfologik_stem` token filter.

## License

Morfologik (Polish) Analysis for ElasticSearch is released under the [MIT License](LICENSE).
