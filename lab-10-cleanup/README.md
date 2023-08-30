# Lab 10 - Cleanup
You can keep the resources you've deployed in these labs running as long as you like.  If you used a free trial, eventually the credits in your account will be exhausted and they'll be automatically shutdown.  Alternatively, you can delete them by following these instructions.

## Delete AuraDS Professional Database
If you deployed a SaaS instance you can delete it in the console.  To do that, open the listing for Neo4j Aura in the Google Cloud console [here](https://console.cloud.google.com/marketplace/product/endpoints/prod.n4gcp.neo4j.io).  Click "MANAGE ON PROVIDER."

![](images/01-console.png)

Click "OK" to confirm that you're ok to be redirected to the Aura console.

![](images/02-console.png)

In the Aura console, click on the red garbage can icon in your "form13" instance.

![](images/03-aura.png)

Type "form13" in the dialog and click "Destroy" to delete your instance.

![](images/04-aura.png)

You'll then see a message that the instance is being destroyed.

![](images/05-aura.png)

A few seconds later, you should see a blank screen with no instances.  At this point, all billing for Neo4j Aura has ceased.

![](images/06-aura.png)

## Delete Vertex AI Resources
You'll want to delete the [Managed Notebook](https://console.cloud.google.com/vertex-ai/workbench/managed). The easiest thing to do is probably just to login to the console [here](https://console.cloud.google.com/vertex-ai) and delete manually.

=
