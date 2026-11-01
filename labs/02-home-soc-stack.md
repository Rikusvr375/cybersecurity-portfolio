# 02 · Home SOC Stack (Kali Purple)

**Goal:** Get hands-on with the tooling a Security Operations Centre analyst uses every day, as preparation for an entry-level SOC role and CySA+.

## Components

| Function | Tool |
|---|---|
| Log collection, search & dashboards | **ELK Stack** (Elasticsearch, Logstash, Kibana) |
| Network intrusion detection | **Suricata** |
| Full packet capture & session search | **Arkime** |
| Case management & incident tracking | **TheHive** |

## What I did

- Installed Kali Purple and configured each SOC component.
- Connected the pieces so alerts and logs can be followed from detection through to a tracked case.
- Used the stack to practise the analyst workflow: alert, investigate, gather evidence, record the case.

## What I learned

- How the parts of a SOC fit together: detection alone is useless without somewhere to investigate and record it.
- Why log volume and tuning matter; untuned IDS rules produce noise that hides real alerts.
- The difference between an alert, an event and an incident in practice.

**Tools:** Kali Purple · Elasticsearch · Logstash · Kibana · Suricata · Arkime · TheHive
