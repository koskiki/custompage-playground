# custompage-playground
Power Apps model-driven playground solution for testing different custom page capabilities.

Shout-out to Benedikt Bergmann for generic script example
https://benediktbergmann.eu/2023/08/15/generic-ts-js-to-open-a-custom-page/

## 1. Import solution
Download unmanaged or managed solution to your computer and then import solution to your own developer/sandbox environment.

## 2. Configure playground record
Open Playground model-driven application and create new playground record

Init record with these values:

| Field | Value |
| --- | --- |
| Name (Schema) | List all new or modified files |
| Title | Custom Dialog Title |
| Table Name | kk_playground |
| Record Id | (take from url after first save) |
| Width | 800 |
| Height | 600 |
| Target | Full Page (1) / Dialog (2) / Side Pane (3) |
| Position | Center (1) / Side pane (2) |
| Icon | WebResources/cat_ic_fluent_flash_28_regular |

## 3. Start play with playground
Open custom page from command bar with different parameters to test it out
Navigate forward from custom page using defined buttons and test how navigation path works