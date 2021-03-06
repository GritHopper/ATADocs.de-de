---
title: ATA Health Center | Microsoft ATA
description: "Mit ATA Health Center lässt sich die Integrität des ATA-Diensts überprüfen, und es werden Warnungen über mögliche Probleme angezeigt."
keywords: 
author: rkarlin
manager: mbaldwin
ms.date: 04/28/2016
ms.topic: article
ms.prod: 
ms.service: advanced-threat-analytics
ms.technology: 
ms.assetid: d6c783b2-46c5-4211-b21a-d6b17f08d03d
ms.reviewer: bennyl
ms.suite: ems
translationtype: Human Translation
ms.sourcegitcommit: 050f1ef0b39d69b64ede53243a7fa2d33d0e4813
ms.openlocfilehash: 9f408d7c2cb9c14caee175a1dd1c9ddb1baf9faa


---

*Gilt für: Advanced Threat Analytics Version 1.7*



# ATA Health Center
Mit ATA Health Center lässt sich die Leistung des ATA-Diensts überprüfen, und es werden Warnungen über Probleme angezeigt.

## Arbeiten mit dem ATA Health Center
Das ATA Health Center zeigt Probleme durch einen roten Punkt über dem Health Center-Symbol auf der Menüleiste an.

![Roter Punkt auf der Symbolleiste für das ATA-Integritätscenter](media/ATA-Health-Center-Alert-red-dot.png)

### Verwalten der ATA-Integrität
Um den Gesamtzustand des Systems zu überprüfen, klicken Sie auf der Menüleiste auf das Health Center-Symbol. ![ATA Health Center-Symbol](media/ATA-red-dot.png)

-   Alle offenen Warnungen lassen sich über die Einstellungen **Aufgelöst** und **Verworfen** verwalten. Klicken Sie hierzu in der Warnung auf **Öffnen**, und scrollen Sie abwärts zu **Aufgelöst** oder **Verworfen**.

-   Wenn ein Problem als behoben markiert wird, ATA jedoch erkennt, dass das Problem weiterhin besteht, wird es automatisch erneut in die Liste der Probleme mit dem Zustand **Offen** aufgenommen. Wenn ATA erkennt, dass ein offenes Problem behoben wurde, wird dieses automatisch in die Liste **Aufgelöst** aufgenommen.

-   Probleme mit dem Status **Verworfen** sind solche, die ATA nicht länger überprüfen soll – beispielsweise bekannte Probleme, die derzeit nicht behoben werden sollen und nicht mehr in der Liste **Offen** aufgeführt werden sollen. Legen Sie für solche Probleme **Verworfen** fest.

![Abbildung eines ATA Health Center-Problems](media/ATA-Health-Issue.JPG)

## Weitere Informationen
- [Arbeiten mit ATA-Erkennungseinstellungen](working-with-detection-settings.md)
- [Arbeiten mit verdächtigen Aktivitäten](working-with-suspicious-activities.md)
- [Weitere Informationen finden Sie im ATA-Forum.](https://social.technet.microsoft.com/Forums/security/home?forum=mata)



<!--HONumber=Aug16_HO5-->


