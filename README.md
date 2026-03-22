# DEAR
مكتب الخدمات العقارية
# DEAR
مكتب الخدمات العقارية

## تشغيل التطبيق

1. تثبيت الحزم

```bash
npm install
```

2. اختيار مصدر البيانات (افتراضيًا ملف data.json)

- MongoDB: `DB_TYPE=mongodb` و`MONGODB_URI=mongodb://localhost:27017/dear`
- PostgreSQL: `DB_TYPE=postgres` و`POSTGRES_URI=postgres://user:pass@host:5432/dear`
- ملف JSON: `DB_TYPE=file`

3. تشغيل السيرفر

```bash
DB_TYPE=mongodb npm start
```

4. افتح المتصفح

- لوحة السوق: http://localhost:4000/
- لوحة الإدارة: http://localhost:4000/admin.html

## وظائف متوفرة

- إضافة منطقة جديدة، نوع عقار جديد
- إضافة عقارات بالفيديو/سعر/موقع/مساحة
- تصفية منتجات السوق بالعربية
cd /workspaces/DEAR
npm install

