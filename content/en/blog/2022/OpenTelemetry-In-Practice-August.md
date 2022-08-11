---
title: OpenTelemetry in Practice - Kubernetes & the Collector
linkTitle: OTel in Practice
date: 2022-08-11
author: Rynn Mancuso
draft: true
# TODO: remove this line once your post is ready to be published
# TODO: run the following command before submitting
#   npx prettier --write content/en/blog/2022/OpenTelemetry-In-Practice-August.md
---

## About the OpenTelemetry in Practice Series

Welcome to the OpenTelemetry in Practice series! This is a new experiment by
some OpenTelemetry contributors in the End User Working Group.

We’re aiming to:

- address practical problems that commonly stop development teams from
  succeeding with OpenTelemetry
- build stronger connections with developers focused on specific languages
- improve the experience of implementing OpenTelemetry in production

Each OpenTelemetry in Practice session will include a half hour of lightning
talks and a half hour of open conversation about the topic. We are looking for
people to join the OpenTelemetry in Practice team and people to give talks at
future events - so if you’re interested in shaping these conversations, please
reach out in the #otel-user-research channel in the CNCF Slack.

Our first conversation will be on August 23rd, at 10 AM PDT, [on Zoom](), and
the topic is Kubernetes & The Collector. Our lightning talks include:

## Observability Pipelines for Kubernetes - Daniel Kim, New Relic

When doing observability, we need to collect signals from many different data
sources, frameworks and programming languages. We can turn heterogeneous data
across so many different signals into actionable insights through a framework
like OpenTelemetry. In this talk Daniel will show you how to build an
observability data pipeline using the OpenTelemetry Collector and open source
plugins that can perform a wide variety of data processing, such as injecting
infrastructure metadata into traces and metrics, implementing tail-based
sampling, and exporting data to any backend via OTLP. Finally, he will share
some of the challenges with running the Collector, so that you can take them
into account as you build out your own observability pipeline with
OpenTelemetry.

## Collector Configuration and Troubleshooting in Kubernetes - Jessica Kerr, Honeycomb

Ah, the Collector: it is our friend, but sometimes it is a difficult friend.
Let’s talk about getting the OpenTelemetry Collector working in Kubernetes. Jess
will run the Collector using the OpenTelemetry helm chart, and then tweak the
configuration until it works. She’ll demonstrate two techniques for
troubleshooting and warn about some pitfalls. Then, share your victories and
frustrations with the Collector, as we learn to be better friends with it,
together.