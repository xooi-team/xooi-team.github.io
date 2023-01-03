---
title: Aktiviteler
layout: default
nav_order: 4
---
## Aktiviteler
{: .text-blue-100 .fs-8}
---
#### Aktiviteler Listesi

Aktiviteleri filtreleme, sıralama yaparak sonuçları sayfalara göre listeler.
Aktivitelerde farklı arama setleri için filitre setleri kullanılabilir. 
Listedeki kolonlar kolon filitresi ile görünürlüğü değiştirilebilir. 

![ActivitySearch](/images/activitiy.png)

| Parametre | Tip     | Açıklama                |
| :-------- | :------- | :------------------------- |
| `page` | `int` | **Gerekli**. Liste sayfa numarası |
| `pageSize` | `int` | **Gerekli**. Sayfada bulunacak sonuç sayısı |
| `orderBy` | `enum` | Sıralama yapılacak kolon |
| `orderType` | `enum` | Sıralama türü |
| `filter` | `filter` |filtreleme yapılacak kolon|

![ActivityListView](/images/activityListView.png)

#### Servisler ve İşlemler
```http
  POST /api/Activity/Search
```

#### DB Design
![ActivityDBDesign](/images/activityDBDesign.png)


#### Yetkiler ve Süreç

#### Aktivite Detay



