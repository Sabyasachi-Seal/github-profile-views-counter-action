<div align="center">
  <h1>GitHub Insights</h1>
</div>
<div align="center" margin>
  <p>Shows number of page views and unique visitors breakdown per week, month, and year of your repositories using <strong>GitHub Actions</strong>.<br/>
    The github-insights action updates the insights fetched from <strong>GitHub API</strong> for every 6 hours.<br/>
    This action is written by gayanvoice. Don't forget to follow me on GitHub and Twitter.</p>
</div>

### Step 1 - ⚡️ Create a repository from the template 

- Star ⭐ this repository 😉
- Go to the [template repository](https://github.com/gayanvoice/github-insights-template) of this GitHub Action.
- Click on `Use this template` button on the top-right.
- Enter a name for `Repository name` and select `public` option.
- Click on `Create repository from template` to create the repository.

**Billing note:** GitHub offers [unlimited build minutes](https://github.com/pricing) for `pubic` repositories. If you select `private` option when you create the repository you have to pay for build minutes or limit the number of build jobs in `- cron` option in [action.yml](https://github.com/gayanvoice/github-insights-template/blob/master/.github/workflows/action.yml) of your repository.

### Step 2 - Add repository secrets

- Click on your profile picture on the top-right corener and select `Settings` option.
- In the left sidebar, select `Developer settings` option.
- In the left sidebar, click on `Personal access tokens` option.
- Click on `Generate new token` button.
- Go to [Personal Access Tokens](https://github.com/settings/tokens) in Developer settings.
<table>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>
