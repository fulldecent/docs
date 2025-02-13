---
title: Deploy
---

Compile and deploy the contract.

## Local

Run this command by right clicking anywhere on the contract and selecting **Aion Virtual Machine** > **Embedded** > **Deploy**.

![Deploy to Embedded AVM](images/deploy-to-embedded.gif)

You should see a notice when the contract has successfully deployed:

![Successful Deployment Notice](images/successful-deployment-notice.png)

## Remote

Run this command by right clicking anywhere on the contract and selecting **Aion Virtual Machine** > **Remote** > **Deploy**. You will be prompted to enter a [node URL](configure#remote-kernel) and [deployer address](configure#remote-kernel) if you haven't filled them in already.

This command will compile your contract before attempting to deploy, unless you have specified that you do not want this to happen in the [configuration options](configure#remote-kernel).
