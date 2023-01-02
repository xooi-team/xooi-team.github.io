---
title: Müşteri Adayları
layout: default
nav_order: 2
---
## Müşteri Adayları
{: .text-blue-100 .fs-8}
---

#### Search

Müşteri Adayı

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



