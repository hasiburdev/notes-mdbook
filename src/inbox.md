# Inbox

This place is to keep random notes. Will organize sometime in future.

- [ ] Activity
  - [ ] Commenting on Posts
  - [ ] Small video about porofolio website
- [ ] Prepare message format

## Azure Node.js Server Deploy with CLI.

Installing Azure CLI on Linux.
Use this oneline command to install Azure CLI on linux.

```bash
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash
```

Login to Azure Account

```bash
az login
```

Deploying nodejs app for the first time.

```bash
az webapp up --sku F1 --name project_name
```

Here `--sku F1` is for Free Tier linux server and `--name project_name` is a unique name for the project.

To redeploy a Server, just run this command in the project folder.

```bash
az webapp up
```

To view logs of the server, run this command:

```bash
az webapp log tail
```

To delete the project from azure, run this commad:

```bash
az group delete
```

To exit before finishing delete process, run:

```bash
az group delete --no-wait
```

## Testing

Check the Testing Playground service.

```ts
screen.logTestingPlaygroundURL();
screen.debug();
```
