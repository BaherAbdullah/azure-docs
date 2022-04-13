---
title: How to send a Conversational Language Understanding job
titleSuffix: Azure Cognitive Services
description: Learn about sending a request for Conversational Language Understanding.
services: cognitive-services
author: aahill
manager: nitinme
ms.service: cognitive-services
ms.subservice: language-service
ms.topic: how-to
ms.date: 03/15/2022
ms.author: aahi
ms.devlang: csharp, python
ms.custom: language-service-clu, ignite-fall-2021
---

# Deploy and test a conversational language understanding model

After you have [trained a model](./train-model.md) on your dataset, you're ready to deploy it. After deploying your model, you'll be able to query it for predictions. 

> [!Tip]
> Before deploying a model, make sure to view the model details to make sure that the model is performing as expected.

## Deploy model

Deploying a model hosts and makes it available for predictions through an endpoint.

When a model is deployed, you will be able to test the model directly in the portal or by calling the API associated to it.

### Model deployment

1. Go to your project page in Language Studio.
2. Select **Deploy model** from the left side menu.
3. Click on *Add deployment* to submit a new deployment job

    :::image type="content" source="../media/add-deployment-model.png" alt-text="A screenshot showing the model deployment button in Language Studio." lightbox="../media/add-deployment-model.png":::

2. In the window that appears, you can create a new deployment by giving the deployment a name or override an existing deployment. Then, you can add a trained model to this deployment.

    :::image type="content" source="../media/create-deployment-job.png" alt-text="A screenshot showing the add deployment job screen in Language Studio." lightbox="../media/create-deployment-job.png":::

> [!NOTE]
> You can only have ten deployment names.

#### Swap deployments

If you would like to swap the models between two deployments, simply select the two deployment names you want to swap and click on **Swap deployments**. From the window that appears, select the deployment name you want to swap with.

:::image type="content" source="../media/swap-deployment.png" alt-text="A screenshot showing a swapped deployment in Language Studio." lightbox="../media/swap-deployment.png":::

#### Delete deployment

To delete a deployment, select the deployment you want to delete and click on **Delete deployment**.

