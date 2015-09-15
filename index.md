---
layout: default
title: SLAMon
---

# SLAMon

## What is SLAMon?
SLAMon is Service Level Agreement Monitor: A tool for monitoring live business
processes and their live performance as seen by the customer using the business
process.

SLAMon gathers performance data from the whole business process instead
of separate tasks inside the process.  The business process owner defines the
business process test flow and the data gathered from the flow, so that the data
can be aggregated to usable statistics.

SLAMon can be used for example testing whether a cloud service's process time
meets the service level agreement, or whether a given business process in
a cloud works as it is defined to work.

## Features

### [slamon-jbpm](https://github.com/SLAMon/slamon-jbpm)
[![Build Status](https://travis-ci.org/SLAMon/slamon-jbpm.svg?branch=master)](https://travis-ci.org/SLAMon/slamon-jbpm)
[![Download](https://api.bintray.com/packages/slamon/java/slamon-jbpm/images/download.svg)](https://bintray.com/slamon/java/slamon-jbpm/_latestVersion)

JBoss Business Process Management Suite (jBPMS) WorkItemHandler
implementation for sending tasks to AFM to be executed by Agents

### [slamon-agent-fleet-manager](https://github.com/SLAMon/slamon-agent-fleet-manager)
[![Build Status](https://travis-ci.org/SLAMon/slamon-agent-fleet-manager.svg?branch=master)](https://travis-ci.org/SLAMon/slamon-agent-fleet-manager)
[![Latest PyPI Version](https://badge.fury.io/py/slamon-afm.svg)](http://badge.fury.io/py/slamon-afm)

Receives tasks from Business Process Management Suite and gives received
tasks to polling Agents

### [slamon-python-agent](https://github.com/SLAMon/slamon-python-agent)
[![Build Status](https://travis-ci.org/SLAMon/slamon-python-agent.svg?branch=master)](https://travis-ci.org/SLAMon/slamon-python-agent)
[![Latest PyPI Version](https://badge.fury.io/py/slamon-agent.svg)](http://badge.fury.io/py/slamon-agent)

Agent implementation and SDK in Python

### [slamon-java-lib](https://github.com/SLAMon/slamon-java-lib)
[![Build Status](https://travis-ci.org/SLAMon/slamon-java-lib.svg?branch=master)](https://travis-ci.org/SLAMon/slamon-java-lib)
[![Download](https://api.bintray.com/packages/slamon/java/slamon-lib/images/download.svg)](https://bintray.com/slamon/java/slamon-lib/_latestVersion)

Agent SDK in Java

### [slamon-android](https://github.com/SLAMon/slamon-android)
[![Build Status](https://travis-ci.org/SLAMon/slamon-android.svg?branch=master)](https://travis-ci.org/SLAMon/slamon-android)
[![Download](https://api.bintray.com/packages/slamon/android/slamon-agent/images/download.svg)](https://bintray.com/slamon/android/slamon-agent/_latestVersion)

Push notifications for alerting about test process situation to the
Android device using JBoss Unified Push
