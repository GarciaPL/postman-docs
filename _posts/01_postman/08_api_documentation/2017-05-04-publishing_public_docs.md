---
categories:
  - "postman"
  - "api_documentation"
title: "Publishing public docs"
page_id: "publishing_public_docs"
warning: false
---

Published documentation is a way of sharing your API documentation with the world. If you’re able to view documentation for one of your collections, publishing docs are a click away! See examples, and read more about [public API documentation](/docs/postman_for_publishers/public_api_docs).

### Generating public documentation

You can only publish documentation for collections that you created or for which you have write permissions. [Open the docs page](/docs/postman/api_documentation/viewing_documentation) for one of your collections. Click the **Publish** button at the top of the screen.

[![publish button](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/59116421.png) ](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/59116421.png)  

If you are signed in to Postman, you can select a corresponding environment with which to publish the collection. Any references to variables like {% raw %}`{{url}}`{% endraw %} in the collection will be replaced with the correct value from the environment. 

[![publish collection settings](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/publishCollectionSettings.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/publishCollectionSettings.png)

The public URL field in the screenshot below contains the URL that you can share with the outside world. For example, if you’re publishing your primary collection, you might want to select the “Production” environment, so that your documentation is immediately usable for new visitors. 

[![published collection settings](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/publishedCollection.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/publishedCollection.png)

> **IMPORTANT:**  Any confidential info in your environment, such as **passwords and access tokens**, might be visible publicly. Ensure that all such information is removed from the environment before you publish documentation with an environment.

The public documentation link will always have the most up-to-date content! You don’t need to keep going through the Publish flow each time you want your docs to be updated.

To unpublish, click the `View Docs` button from your Postman app. Click the **Published** button near the top of the screen. For a collection that’s already been published, you’ll be able to view the public link or unpublish the collection. 

[![publish or unpublish](https://www.getpostman.com/img/v1/docs/publishing_docs/Docs5.png)](https://www.getpostman.com/img/v1/docs/publishing_docs/Docs5.png)

We’ve published documentation for this collection - check it out [here](https://documenter.getpostman.com/view/583/coopers-meal-plan/4u2){:target="_blank"}.

### Custom domains

Optionally, you can pick from a list of verified [custom domains](/docs/postman/api_documentation/adding_and_verifying_custom_domains) to host your API documentation. You’ll be able to view docs on your custom domain, as well as the Postman private documentation page. 

[![custom domain](https://static.getpostman.com/postman-docs/40ce4cda-5788-4e18-9141-4391de078244.png)](https://static.getpostman.com/postman-docs/40ce4cda-5788-4e18-9141-4391de078244.png)

### Custom styling options

Postman allows you to customize the appearance of your published documentation pages. Add your [team logo](/docs/postman/api_documentation/adding_team_name_and_logo) and update the color theme to align with your brand. 

You can update the custom styling options either before or after you publish your documentation. Click the **Show Custom Styling Options** link to expand the section and update your color palette.

[![before publishing](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/customStylingOptions.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/customStylingOptions.png)

[![custom styling options](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/59016798.png)](https://s3.amazonaws.com/postman-static-getpostman-com/postman-docs/59016798.png)
