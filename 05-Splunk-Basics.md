# 05 - Splunk Basics - Did you SIEM?

## What I Learned
- How to ingest and parse custom log data in Splunk
- Basic SPL (Search Processing Language) queries
- Using common commands: `index`, `sourcetype`, `stats`, `table`, `sort`, `head`
- Creating simple searches and dashboards
- Identifying suspicious activities using Splunk

## Key Takeaways
- Understood how Splunk turns raw logs into searchable data
- Learned foundational SPL commands used in real SOC environments
- Gained confidence in writing basic Splunk queries

## Most Useful Commands Learned
- `index=main sourcetype=access_combined`
- `| stats count by status`
- `| table _time, src_ip, action`
- `| sort -count`

## Tools Used
- Splunk Enterprise
- SPL (Search Processing Language)
