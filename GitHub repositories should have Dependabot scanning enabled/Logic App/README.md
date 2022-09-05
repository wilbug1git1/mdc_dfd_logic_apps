# Logic App sample for Enable Dependabot on a repository

This Logic App deployment template is provided to remediate the GitHub repositories should have Dependabot scanning enabled recommendation in Azure Security Center.  The workflow requires a PAT token for authentication to the GitHub API.  It will leverage the following API endpoint to enable Dependabot on a repository: https://api.github.com/repos/{org}/{repository}/vulnerability-alerts

  

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fwilbug1git1%2Fmdc_dfd_logic_apps%2Fgh-dependa-initial-commit%2FGitHub%20repositories%20should%20have%20Dependabot%20scanning%20enabled%2FLogic%20App%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.