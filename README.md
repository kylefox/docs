# RevGems Help Center

This is the repository behind the [RevGems Help Center](https://help.revgems.com/api-reference/introduction).

Have an idea for how we can improve our documentation? Awesome! [Open a new issue](https://github.com/review-rocket/docs/issues/new) to report a problem or make a suggestion. Or better yet, fork this repository and [submit a pull request](https://github.com/review-rocket/docs/pulls) to contribute your changes!

## Powered by Mintlify

The RevGems Help Center is powered by [Mintlify](https://mintlify.com/). If you'd like to contribute improvements, follow the steps below to get things running locally.

### Development

Clone this repository to your local machine:

```bash
git clone git@github.com:review-rocket/docs.git
```

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command:

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is):

```
mintlify dev
```

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
