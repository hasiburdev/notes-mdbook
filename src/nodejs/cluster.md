# Cluster

Check if the current one is cluster manager

```js
cluster.isMaster);
```

Create child instance

```js
cluster.fork();
```

`pm2` is used for clustering in production.

Installing pm2 (I am currently using pnpm)

```bash
pnpm add -g pm2
```

Running a script with `pm2`:

```bash
pm2 start src/index.js -i 0
```

- `-i` flag indicates, number of indicates. `0` value will default to number of logical cores of the cpu.

Monitoring pm2 indicates

```bash
pm2 monit
```

Delete a pm2 app

```bash
pm2 delete app_name
```
