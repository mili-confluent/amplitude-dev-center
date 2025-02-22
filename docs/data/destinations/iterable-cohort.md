---
title: Send Cohorts to Iterable
description: Send Amplitude cohorts to Iterable to use them in your customer engagement efforts. 
---

Send Amplitude cohorts to Iterable to use them in your customer engagement efforts. 

!!!note "Other Amplitude + Iterable integrations"

    This integration sends Amplitude cohorts to Iterable. Amplitude offers other integrations with Iterable: 

    - [Import Iterable Data](/data/sources/iterable)
    - [Stream Amplitude Events to Iterable](/data/destinations/iterable)

## Considerations 

- Amplitude’s `user_id` value maps to Iterable’s `userId`. If these values don't match or the user doesn't exist in Iterable, Iterable generates a dummy placeholder email address.

## Setup

### Prerequisites

Copy your Iterable API key. You can find this in Iterable under **Integrations > API Keys**.

### Amplitude setup

1. In Amplitude, navigate to **Data Destinations**, then find **Iterable - Cohort**.
2. Add your Iterable API key. 
3. Enter a name. 
4. Map the Amplitude user ID.
5. Save your work. 

## Send a cohort

1. In Amplitude, open the cohort you want to export. 
2. Click **Sync**, and choose Iterable.
3. Select the destination.
4. Select the sync cadence.
5. Save when finished.

You can now find the synced behavioral cohort under Iterable's user list. The cohort's name has the `[Amplitude]` prefix.
