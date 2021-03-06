---
title: 'Using snapshots on a VPS'
excerpt: 'Find out how to how enable and use the snapshot option in the OVHcloud Control Panel'
slug: using-snapshots-on-a-vps
section: 'Backup options'
order: 1
hidden: true
---

**Last updated 20th March 2020**


## Objective

> [!primary]
>
Before applying backup options, we recommend to consult the [product page](https://www.ovh.co.uk/vps/backup-vps.xml) for pricing comparisons and further details.
>

Creating a snapshot is a fast and simple way to secure a functioning system before making changes that might have undesired or unforeseen consequences, for example testing a new configuration or software. It does not, however, constitute a complete system backup strategy.

**This guide explains the usage of snapshots for your VPS.**

## Requirements

- access to the [OVHcloud Control Panel](https://www.ovh.com/auth/?action=gotomanager)
- an OVHcloud [VPS service](https://www.ovh.co.uk/vps/) already set up


## Instructions

Log in to your [OVHcloud Control Panel](https://www.ovh.com/auth/?action=gotomanager), navigate to the "Server" section, and select your server from the left-hand sidebar under `VPS`{.action}.

### Step 1: Subscribing to the snapshot option

From the `Home`{.action} tab, scroll down to the box called "Summary of options". Click on `...`{.action} next to the option "Snapshot" and in the context menu click on `Order`{.action}.

![snapshotvps](images/snapshot_vps_step1.png){.thumbnail}

In the new screen, please take note of the pricing information, then click on `Order`{.action}. You will be guided through the order process and receive a confirmation email.

### Step 2: Taking a snapshot

Once the option is enabled, click on `...`{.action} next to the option "Snapshot" and in the context menu click `Take a snapshot`{.action}. Creating the snapshot might take a few minutes. Afterwards, the timestamp of the creation will appear in the "Summary of options".

### Step 3: Deleting / restoring a snapshot

Since you can only have one snapshot activated at a time, the existing snapshot has to be deleted before creating a new one. Simply choose `Delete the snapshot`{.action} from the context menu.

![snapshotvps](images/snapshot_vps_step2.png){.thumbnail}

If you are sure that you want to reset your VPS to the status of the snapshot creation, click `Restore the snapshot`{.action} and confirm the execution in the pop-up window.


## Go further

[Using automated backups on a VPS]()

[Using backup storage on a VPS]()


Join our community of users on <https://community.ovh.com/en/>.