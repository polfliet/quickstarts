[![Community Project header](https://github.com/newrelic/open-source-office/raw/master/examples/categories/images/Experimental.png)](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#experimental)

# New Relic Quickstart

Community repository of New Relic dashboards, alerts, and installation instructions. You can find the repository here: https://newrelic-experimental.github.io/quickstarts/

## Adding your own dashboards, alerts or instructions

1. [Fork the Github repository](https://help.github.com/en/github/getting-started-with-github/fork-a-repo#fork-an-example-repository)

2. [Clone your own repository to your local machine](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

3. Create a directory in the `quickstarts` folder with the name of the technology you have a resources for. For example: `RabbitMQ`, `APM Errors`, ..

4. Add a file called `dashboard.json` to your directory and add the JSON of your dashboard.

5. Create a `config.json` file with the following content:

```
{
    "name": "Name of your dashboard",
    "author": "Your name or email address"
}
```

6. Commit your changes `git add -A` and `git commit -m "My new resource"`. Change the `My new resource` with a description of the resource you've added.

7. Push your changes to Github `git push`

8. [Create a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) in the [parent repository](https://github.com/newrelic-experimental/quickstarts/compare?expand=1).

9. Submit and wait for review. We will review as fast as we can, but it can sometimes take a day or two.

Thanks a lot for your submission!


## Building - optional

Dependencies:

- NodeJS
- Yarn

Pulling in third party dependencies: `yarn`

Building the repository dataset: `./build.sh`

Running the website locally: `yarn run start`

## Support

If you encounter any issues, have feedback or ideas. Please don't hesitate to create a ticket.
<!-- New Relic hosts and moderates an online forum where customers can interact with New Relic employees as well as other customers to get help and share best practices. Like all official New Relic open source projects, there's a related Community topic in the New Relic Explorers Hub. You can find this project's topic/threads here:

>Add the url for the support thread here -->

## Contributing
Full details about how to contribute to
Contributions to improve [Project Name] are encouraged! Keep in mind when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project.
To execute our corporate CLA, which is required if your contribution is on behalf of a company, or if you have any questions, please drop us an email at open-source@newrelic.com.

## License
New Relic quickstarts is licensed under the [Apache 2.0](http://apache.org/licenses/LICENSE-2.0.txt) License.

