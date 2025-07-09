This is a github repo for my github.io website.
# FasterWorkflow endpoint
You may think, why does manual trigger (workflow_dispatch) run instantly than Cron? Well, i made an API that will make it run your workflows (almost) instantly. Using cron-job.org + this API is great AND give you more options (in cron-job.org) like, custom timezones!
## How to use
1. Register a cron-job.org account (if not already)
2. Create a new cron-job.
3. URL: https://Scratch2033Alt.github.io/FasterWorkflow
4. Click "Advanced" then, in headers section, click "New", In the "KeY" type in "Authorization" and in "Value" input your Github PAT.
5. Click "Create" and done! if you want to change the timezone, in the "Advanced" section, click "Time zone". Make sure the "Request method" is GET.
