# [Backstage](https://backstage.io)

This is a modified version of the original Backstage (developed by **@backstage**) that I used to play with the integration to Microsoft Entra ID and Azure DevOps.

You can check my tutorials for that below:
- [Authentication on Backstage with Ms Entra ID](https://blog.lmeier.net/posts/authentication-backstage-entra-id/)
- [Integrating Backstage and Azure DevOps](https://blog.lmeier.net/posts/integrating-backstage-azure-devops/)

You can folow my [blog](https://blog.lmeier.net) or [Medium](https://medium.lmeier.net) for new content.

This version already contains the plugins and necessary customizations to be used with those 2 tools. Just change the variables in `app-config.yaml` and `examples/org.yaml` to start playing. Terraform and templates files are under `terraform` and `templates` folders.

To start the app, run:

```sh
yarn install
yarn dev
```

Enjoy!
