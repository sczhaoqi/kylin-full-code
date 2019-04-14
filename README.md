Apache Kylin
============

[![Build Status](https://travis-ci.org/apache/kylin.svg?branch=master)](https://travis-ci.org/apache/kylin)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Coverage Status](https://coveralls.io/repos/github/apache/kylin/badge.svg?branch=master)](https://coveralls.io/github/apache/kylin?branch=master)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/74f0139786cd4e8a8ce69bb0c17c2e71)](https://www.codacy.com/app/kyligence-git/kylin?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=apache/kylin&amp;utm_campaign=Badge_Grade)
[![Quality Gate](https://sonarcloud.io/api/project_badges/quality_gate?project=org.apache.kylin%3Akylin)](https://sonarcloud.io/dashboard/index/org.apache.kylin%3Akylin)
[![SonarCloud Coverage](https://sonarcloud.io/api/project_badges/measure?project=org.apache.kylin%3Akylin&metric=coverage)](https://sonarcloud.io/component_measures/metric/coverage/list?id=org.apache.kylin%3Akylin)
[![SonarCloud Bugs](https://sonarcloud.io/api/project_badges/measure?project=org.apache.kylin%3Akylin&metric=bugs)](https://sonarcloud.io/component_measures/metric/reliability_rating/list?id=org.apache.kylin%3Akylin)
[![SonarCloud Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=org.apache.kylin%3Akylin&metric=vulnerabilities)](https://sonarcloud.io/component_measures/metric/security_rating/list?id=org.apache.kylin%3Akylin)

> Extreme OLAP Engine for Big Data

Apache Kylin is an open source Distributed Analytics Engine, contributed by eBay Inc., provides SQL interface and multi-dimensional analysis (OLAP) on Hadoop supporting extremely large datasets.

For more details, see the website [http://kylin.apache.org](http://kylin.apache.org).

Documentation
=============
Please refer to [http://kylin.apache.org/docs/](http://kylin.apache.org/docs/).

Get Help
============
The fastest way to get response from our developers is to send email to our mail list <dev@kylin.apache.org>,   
and remember to subscribe our mail list via <dev-subscribe@kylin.apache.org>

License
============
Please refer to [LICENSE](https://github.com/apache/kylin/blob/master/LICENSE) file.





<!--
{% comment %}
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to you under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->
[![Build Status](https://travis-ci.org/julianhyde/calcite.svg?branch=master)](https://travis-ci.org/julianhyde/calcite)

# Abount KyCalcite

KyCalcite is a customized calcite for better kylin use. 

Naming convension of different branch is kylin-{CALCITE_VERSION}.x, e.g. kylin-1.13.0.x

Naming convension of different releases (the name could be used for creating git tag, or pom version name), is {CALCITE_VERSION}-kylin-r{RELEASE_NUMBER}, e.g. 1.13.0-kylin-r1

For new KyCalcite releases we need to deploy it to our own Nexus server (kynexus.chinaeast.cloudapp.chinacloudapi.cn:8081), if you don't have enough permission please contact hongbin.ma@kyligence.io

**Since sonar does not allow overriding formal releases, you might choose to use a snapshot version name, e.g. 1.13.0-kylin-r1-SNAPSHOT**

steps:

1. publish the new kycalcite to nexus server
2. change kap and kylin's calcite pom dependency version
3. create a tag for the commit on which the new kycalcite is built from. Don't forget to push tags to server


# Apache Calcite

Apache Calcite is a dynamic data management framework.

For more details, see the [home page](http://calcite.apache.org).
