# TA-markdata

# Overview

## About markData add-on for Splunk

|                          |                                                |
| ------------------------ | ---------------------------------------------- |
| Author                   | Josh Wilson                                   |
| App Version              | 0.0.0                                          |
| App Build                | 1                                             |
| Creates an index         | false                                          |
| Implements summarization | Currently, the app does not generate summaries |

Dashboards and reports on Bricata Metadata and alerts in Splunk.

## Scripts and binaries

  - None

# Release notes

## Version 0.0.1

  - beta Release

## About this release

Version 0.0.1 of markData add-on for Splunk is compatible with:

|                            |                   |
| -------------------------- | ----------------- |
| Splunk Enterprise versions | 8.x          |
| Platforms                  | Splunk Enterprise |

## Overview

This TA is designed to allow for marking and grouping of data being searched through using workflow actions..  There are three categories; pertinent, needs_review and non_pertinent.  These markings are stored in a kvstore.

## Available Dashboards

  - None

### Sourcetypes (Advanced)

  - None

## Prerequisites

### Splunk Versions

This add-on has been tested with Splunk versions 8.0.2.1. 


### Simple Installation Process


  - Install the markData add-on for Splunk.
  - Use the workflow actions to mark data.

### References



### Downloads



## Known Issues

Version 1.0.0 of markData add-on for Splunk has the following known issues:

  - None

# Support and resources

## Questions and answers

    -Here

## Support

  - Support Email: joshua.wilson@augustschell.com

# Installation and Configuration

## Software requirements

### Splunk Enterprise system requirements

Because this App runs on Splunk Enterprise, all of the [Splunk Enterprise system requirements](https://docs.splunk.com/Documentation/Splunk/latest/Installation/Systemrequirements) apply.

## Download

    -Here

## Installation steps

### Deploy to single server instance

Follow these steps to install the add-on in a single server instance of Splunk Enterprise:

1.  Deploy as you would any add-on, and restart Splunk.
2.  Configure.


### Deploy to a Distributed Environment

1.  For each Search Head in the environment, deploy a copy of the add-on.

# User Guide

## Configure markData add-on for Splunk

  - Install the App according to your environment (see steps above)

## Lookups

markData add-on for Splunk contains the following collections.

  - markData_correlation

## Event Generator

markData add-on for Splunk does not include an event generator.

## Acceleration

1.  Summary Indexing: No
2.  Data Model Acceleration: No
3.  Report Acceleration: No

# Third Party Notices

Version 0.0.1 of markData add-on for Splunk incorporates the following Third-party software or third-party services.

  - None

### Related Topics

  - [Documentation overview](index.html#document-index)

2020, August Schell
