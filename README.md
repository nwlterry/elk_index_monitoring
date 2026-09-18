# elk_index_monitoring

Kibana 8.15 saved objects for **ELK System Index Size & Trend Monitor** (`.kibana`, `.security`, `.monitoring`, other `^\..*` names) from Metricbeat `elasticsearch.index.stats`.

## Layout

```
dashboards/elk-system-index-monitor-dashboard.json
GROUP.md
README.md
```

Expected index pattern: `metricbeat-*`. Import: **Stack Management → Saved Objects → Import**.

---

See [GROUP.md](GROUP.md) for sibling repositories. Catalog: https://github.com/nwlterry/nwlterry
