# git-template-spec-sync
Syncs an Azure ARM template from GitHub to a Template Spec using Actions.

Pre-reqs:
- Update .github/workflows/workflow.yml with the values for your environment
- Configure deployment credentials: https://github.com/marketplace/actions/azure-login#configure-deployment-credentials
- Update the URI in the button below, or add a new step to the workflow to automate

Once synched, click below to deploy from your template spec: should work even from Private Repos :)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/templateSpecVersionId/%2fsubscriptions%2f<<subscription_id>>%2fresourceGroups%2f<<resource_group_name>>%2fproviders%2fMicrosoft.Resources%2ftemplateSpecs%2f<<template_spec_name>>%2fversions%2f<<version>>)