# elk_index_monitoring

Kibana 8.15 saved-object export for **ELK System Index Size & Trend Monitor**.

The dashboard tracks size and growth of Elasticsearch system indices (`.kibana`, `.security`, `.monitoring`, and other names matching `^\..*`) from Metricbeat `elasticsearch.index.stats`.

## File

`elk-system-index-monitor-dashboard` — JSON export of the dashboard plus visualizations:

- Total system index size over time
- Size breakdown (pie)
- Top 10 largest system indices
- Daily growth
- Index count metrics

Expected data view / index pattern: `metricbeat-*`.

Import in Kibana: **Stack Management → Saved Objects → Import**.
