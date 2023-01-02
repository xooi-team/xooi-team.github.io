---
title: Müşteriler
layout: default
nav_order: 3
---
## Activity
{: .text-blue-100 .fs-8}
---

#### Search

Müşteri

![ActivitySearch](/images/activitiy.png)

```http
  POST /api/Activity/Searchß
```

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `page` | `int` | **Gerekli**. Liste sayfa numarası |
| `pageSize` | `int` | **Gerekli**. Sayfada bulunacak sonuç sayısı |
| `orderBy` | `enum` | Sıralama yapılacak kolon |
| `orderType` | `enum` | Sıralama türü |
| `filter` | `filter` |filtreleme yapılacak kolon|



![ActivityListView](/images/activityListView.png)



