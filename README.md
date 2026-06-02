# Shadow IT Detection Framework

## Overview

This project provides a lightweight and cost-effective solution for detecting unauthorized cloud services and applications (Shadow IT) operating within an organization's network. Instead of inspecting encrypted packet contents, the framework analyzes network traffic metadata to identify potentially illegitimate applications.

## Key Features

* Detects unauthorized cloud applications and services used without IT department approval.
* Utilizes Zeek network monitoring for efficient traffic analysis.
* Analyzes encrypted traffic metadata such as:

  * Server Name Indication (SNI)
  * Destination IP addresses
  * Domain names
  * Connection-related network information
* Generates real-time alerts for suspicious or unauthorized application usage.
* Maintains detailed logs for security monitoring and auditing purposes.
* Provides visualization capabilities for network activity and detected Shadow IT instances.
* Works without machine learning models, reducing computational overhead and complexity.
* Supports scalable deployment across organizational networks.

## Benefits

* Improves visibility into hidden or unmanaged cloud application usage.
* Helps reduce cybersecurity risks and potential data breaches.
* Assists organizations in maintaining compliance with internal security policies.
* Offers a practical and affordable alternative to expensive commercial security solutions.
* Enables continuous monitoring of encrypted network traffic while preserving privacy.
