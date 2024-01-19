---
layout: post
title: "Datadog Integration"
date: 2023-05-27
description : "How to create Datadog Integration"
---

# Datadog

# Datadog Agent

# Datadog integration

Integrations enable you to collect data on specific services using Datadog. You can use Integrations to bring together metrics and logs from your infrastructure and applications into Datadog to gain insight into the unified system as a whole.

Datadog provides three main types of integrations:

- Agent-based integrations are installed with the Datadog Agent and use a Python class method called check to define the metrics to collect. 
- Authentication (crawler) based integrations are set up in Datadog where you provide credentials for obtaining metrics with the API. These include popular integrations like Slack, AWS, Azure, and PagerDuty.
- Library integrations use the Datadog API to allow you to monitor applications based on the language they are written in, like Node.js or Python.

Many times, Datadog's library of over 400 built-in integrations is sufficient for your use case. However, if you are releasing your own service that you would like to integrate with Datadog or would like a custom integration, you can build your own!
