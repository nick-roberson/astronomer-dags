Deploy Dags to Astronomer Cloud
===============================

Ensure that you have the following envrionment variables set in your shell:

```bash
export DEPLOYMENT_ID=<your_deployment_id>
export ASTRO_API_TOKEN=<your_api_token>
```

Then run the following command to deploy your dags to Astronomer Cloud:
```bash
astro deploy --dags
```

To force a redeploy of all dags, use the `--force` flag:
```bash
astro deploy --dags --force
```

For more information on deploying to Astronomer Cloud, see the [Astronomer Cloud documentation](https://www.astronomer.io/docs/cloud/stable/develop/deploy-dags/).

