## Soal 1

Skiljek dengan data: 
- Full Name
- Email
- Phone Number

One-to-One Relationships
```json
{
    "_id": ObjectId("612d1e835ebee16872a109a4"),
    "full_name": {
        "first_name": "Putra",
        "last_name": "Harianja"
    },
    "email": "putra@mail.com",
    "phone": "08982823170"
}
```


## Soal 2

SkilShop dengan data: 
- Full Name
- Phone Number
- Adress (Max 2)

One-to-Few Relationships
```json
{
    "_id": ObjectId("612d1e835ebee16872a109a4"),
    "full_name": {
        "first_name": "Putra",
        "last_name": "Harianja"
    },
    "phone": "08982823170",
    "addresses": [
        {
            "address": "jln.Kos Abadi Jaya",
            "type": "Rumah Utama"
        },
        {
            "address": "jln.Jaya Sementara",
            "type": "Rumah Dinas"
        }
    ]
}
```

## Soal 3

