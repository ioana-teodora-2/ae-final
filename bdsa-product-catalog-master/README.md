# bdsa-product-catalog

# git clone

```bash
git clone https://github.com/ioana-teodora-2/ae-final.git
```

```bash
cd ae-final/bdsa-product-catalog-master
```

```bash
npm install
```

# install mysql

```bash
mysql-ctl start
```

```bash
mysql -u root
```

```sql
source ~/workspace/bdsa-product-catalog-master/sql/catalog.sql
```

```sql
INSERT INTO categories (name, description) VALUES ('Carti','Cele mai tari carti');
```

```sql
INSERT INTO products (name, description, category_id, price) VALUES ('Clean Code', 'Make code great again!', 1, 100);
```

```sql
exit
```

# run server.js

```bash
node server.js
```

(or in Cloud9 open file and press Run)

