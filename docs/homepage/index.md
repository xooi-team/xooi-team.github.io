---
title: Ana Sayfa
layout: default
nav_order: 1
---
## Ana Sayfa
{: .text-blue-100 .fs-8}
---

#### Search

Ana Sayfa 

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



