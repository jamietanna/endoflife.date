---
title: Elastic Beats
category: server-app
tags: elastic
iconSlug: beats
permalink: /beats
alternate_urls:
-   /elastic-beats
-   /filebeat
-   /metricbeat
-   /packetbeat
-   /winlogbeat
-   /auditbeat
-   /heartbeat
-   /functionbeat
releasePolicyLink: https://www.elastic.co/support_policy
changelogTemplate: "https://www.elastic.co/guide/en/beats/libbeat/{{'__LATEST__'|split:'.'|pop|join:'.'}}/release-notes-__LATEST__.html"
eolColumn: Support
releaseDateColumn: true

auto:
-   git: https://github.com/elastic/beats.git

releases:
-   releaseCycle: "8"
    # the longest between this date and 6 months after the 9.0.0
    eol: 2024-08-10
    latest: "8.9.0"
    latestReleaseDate: 2023-07-25
    releaseDate: 2022-02-10

-   releaseCycle: "7"
    # Maintained until 9.0.0
    eol: 2023-08-01
    latest: "7.17.12"
    latestReleaseDate: 2023-07-25
    releaseDate: 2019-04-05

-   releaseCycle: "6"
    eol: 2022-02-10
    latest: "6.8.23"
    latestReleaseDate: 2022-01-13
    releaseDate: 2017-11-08

---

> [Beats](https://www.elastic.co/beats/) are a suite of lightweight shippers for Elasticsearch and
> Logstash. As of 2022, the beats family is composed of
> [Filebeat](https://www.elastic.co/beats/filebeat),
> [Metricbeat](https://www.elastic.co/beats/metricbeat),
> [Packetbeat](https://www.elastic.co/beats/packetbeat),
> [Winlogbeat](https://www.elastic.co/beats/winlogbeat),
> [Auditbeat](https://www.elastic.co/beats/auditbeat),
> [Heartbeat](https://www.elastic.co/beats/heartbeat) and
> [Functionbeat](https://www.elastic.co/beats/functionbeat).

Beats are part of the [Elastic Stack](https://www.elastic.co/elastic-stack/), also known as the
[ELK Stack](https://www.elastic.co/what-is/elk-stack). It shares the same support policy as the
other products in the Elastic Stack (Elasticsearch, Logstash, Kibana...).

Elastic Stack product releases follow [Semantic Versioning](https://semver.org/). Elastic provides
maintenance for each major release series for the longest of 30 months after the GA date of the
major release or 6 months after the GA date of the subsequent major release.

End of life dates for Beats can be found on the [Elastic product EOL dates page](https://www.elastic.co/support/eol).
Support for various operating systems can also be found on the [Elastic support matrix page](https://www.elastic.co/support/matrix).

*[GA]: General Availability
*[EOL]: End Of Life
