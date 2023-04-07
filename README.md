First, create the database:
```
createdb shopping-cart
```

If you have the make utility installed, run:
```
make
```

Otherwise, manually run the commands:
```
cat customer.sql addresses.sql cart.sql product.sql cart_item.sql seed.sql > shopping-cart.sql
psql shopping-cart < shopping-cart.sql

```
