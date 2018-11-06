Quickstart Guide
================

Let's get started with **Fluentd**! **Fluentd** is a fully free and
fully open-source log collector that instantly enables you to have a
'**Log Everything**' architecture with [600+ types of
systems](http://fluentd.org/plugin/).

![](/images/fluentd-architecture.png)
Fluentd treats logs as JSON, a popular machine-readable format. It is
written primarily in C with a thin-Ruby wrapper that gives users
flexibility.

Fluentd's scalability has been proven in the field: its largest user
currently collects logs from **500,000+ servers**.


### Table of Contents

-   [Step1: Installing Fluentd](#step1:-installing-fluentd)
-   [Step2: Use Cases](#step2:-use-cases)
-   [Step3: Learn More](#step3:-learn-more)
Step1: Installing Fluentd
-------------------------

Please follow the installation/quickstart guides below that matches your
environment.

-   [Install Fluentd by RPM package](install-by-rpm) (Redhat Linux)
-   [Install Fluentd by Deb package](install-by-deb) (Ubuntu/Debian
    Linux)
-   [Install Fluentd by DMG package](install-by-dmg) (Mac OS X)
-   [Install Fluentd by Ruby Gem](install-by-gem)
-   [Install Fluentd by Chef](install-by-chef)
-   [Install Fluentd from source](install-from-source)

Fluentd v0.12 doesn\'t support Windows environment. Please see
[Collecting Log Data from Windows](windows) for details. Fluentd v1.x
supports Windows.

Step2: Use Cases
----------------

The articles shown below cover the typical use cases of Fluentd. Please
refer to the article(s) that suits your needs.

-   Use Cases
    -   [Data Search like Splunk](free-alternative-to-splunk-by-fluentd)
    -   [Data Filtering and Alerting](splunk-like-grep-and-alert-email)
    -   [Data Analytics with Treasure Data](http-to-td)
    -   [Data Collection to MongoDB](apache-to-mongodb)
    -   [Data Collection to HDFS](http-to-hdfs)
    -   [Data Archiving to Amazon S3](apache-to-s3)
    -   [Windows Event Collection](windows)
-   Basic Configuration
    -   [Config File](config-file)
-   Application Logs
    -   [Ruby](ruby), [Java](java), [Python](python), [PHP](php),
        [Perl](perl), [Node.js](nodejs), [Scala](scala)
-   Happy Users :)
    -   [Users](users)

Step3: Learn More
-----------------

The articles shown below will provide detailed information for you to
learn more about Fluentd.

-   [Architecture Overview](architecture)
-   [Life of a Fluentd Event](life-of-a-fluentd-event)
-   Plugin Overview
    -   [Input Plugins](input-plugin-overview)
    -   [Output Plugins](output-plugin-overview)
    -   [Buffer Plugins](buffer-plugin-overview)
    -   [Filter Plugins](filter-plugin-overview)
    -   [Parser Plugins](parser-plugin-overview)
    -   [Formatter Plugins](formatter-plugin-overview)
-   [High Availability Configuration](high-availability)
-   [FAQ](faq)


Last updated: 2017-03-08 14:51:05 UTC
------------------------------------------------------------------------
Versions \| [v1.0 (td-agent3)](/v1.0/articles/quickstart) \| ***v0.12*(td-agent2) **
------------------------------------------------------------------------

If this article is incorrect or outdated, or omits critical information,
please [let us
know](https://github.com/fluent/fluentd-docs/issues?state=open).
[Fluentd](http://www.fluentd.org/) is a open source project under [Cloud
Native Computing Foundation (CNCF)](https://cncf.io/). All components
are available under the Apache 2 License.