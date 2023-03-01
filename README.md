# Keystone `--with-migrations` reproduction repo

### WORKING:

1. `keystone build`
2. `keystone prisma migrate deploy --frozen`
3. `keystone start`

### NOT WORKING:

1. `keystone build`
2. `keystone start --with-migrations`
