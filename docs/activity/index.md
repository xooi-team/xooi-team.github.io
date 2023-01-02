---
title: Aktiviteler
layout: default
nav_order: 4
---
## Aktiviteler
{: .text-blue-100 .fs-8}
---


#### Search

Aktiviteleri filtreleme, sıralama yaparak sonuçları sayfalara göre listeler.

![ActivitySearch](/images/activitiy.png)

```http
  POST /api/Activity/Search
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `page` | `int` | **Gerekli**. Liste sayfa numarası |
| `pageSize` | `int` | **Gerekli**. Sayfada bulunacak sonuç sayısı |
| `orderBy` | `enum` | Sıralama yapılacak kolon |
| `orderType` | `enum` | Sıralama türü |
| `filter` | `filter` |filtreleme yapılacak kolon|



![ActivityListView](/images/activityListView.png)



