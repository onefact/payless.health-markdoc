### Building the website

Clone the repo:
```
git clone https://github.com/onefact/payless.health.git
```

If needed, install the node package manager `npm` and the Node Javascript package with Homebrew on Mac -- `brew install node` after [installing Brew using this link](https://brew.sh/). On Windows, use Chocolatey to install by running `choco install nodejs-lts` after [installing Chocolatey](https://chocolatey.org/install).

Install the dependencies for Markdoc:
```
cd payless.health
npm install --legacy-peer-deps
```

Run the website generation with the node package manager:
```
npm run dev
```

In a web browser, navigate to [http://localhost:3000](http://localhost:3000) to view any changes you make to the code.

We recommend Visual Studio Code to edit this website (you can also install this with Homebrew or Chocolatey).

## Funding

We received a grant from Columbia University and Stanford University through their Brown Institute for Media Innovation: https://brown.columbia.edu/22-23-magic/

## Legal Status

We are a 501(c)(3) nonprofit foundation -- the One Fact Foundation -- headquartered in New York City.

## Plan

Now we are working with dolthub.com to link negotiated rates with prices at every one of 7000+ hospitals in the United States. 

We are conducting user research in disadvantaged areas (as measured by household income below $50,000 and at least one household member on Medicaid health insurance), starting in New York before expanding nationwide:

<img width="1271" alt="image" src="https://user-images.githubusercontent.com/5317244/195488758-71cc8cfa-e853-4854-b5ff-40162dd67d03.png">

The roadmap is here: https://github.com/orgs/onefact/projects/2 

## Key Performance Indicator

Our KPI is the median price of hospital procedures, treatments, medications in the United States across all negotiated rates and hospital prices. If this decreases every quarter, we get promoted.

## Talk Website

![Vercel](https://therealsujitk-vercel-badge.vercel.app/?app=onefact-org) [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

This code uses [Markdoc](https://markdoc.dev) as a backbone to render the One Fact Foundation website, alongside the rest of our web properties.

### Deploy to Vercel to build your own website using our code!

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fonefact%2Fonefact.org&demo-title=One%20Fact%20Foundation%20Website&demo-url=onefact.org&demo-image=https%3A%2F%2Fwww.onefact.org%2Fimages%2Fshare.png&install-command=npm%20install%20--legacy-peer-deps) 

### Deploy using GitHub Pages

GitHub Pages does not support some features of `Next.js` as this library is maintained and aligned with Vercel whose business model depends on differentiating features from GitHub Pages. 

One example is [incremental static regeneration](https://nextjs.org/docs/basic-features/data-fetching/incremental-static-regeneration), which is critical to some of our web properties at the One Fact Foundation. 

You can use this GitHub Action to deploy the website using only GitHub technology: https://github.com/onefact/onefact.org/blob/main/.github/workflows/nextjs.yml

If you cannot afford Vercel and need any help deploying to GitHub Pages please email us at hello@onefact.org and we will do our best to help :)

We got to give a talk at an NIH conference called aim-ahead.net recently on the state of the US healthcare system, and what we can do about it: https://bit.ly/onefact-keynote

## Newsletter

Subscribe to our mailing list to learn when we launch: https://tinyletter.com/payless-health

## Licensing

Software is Apache 2.0. Content is CC-BY-SA 4.0.

## Contact

Say hi! If you have a story to share about your journey trying to pay less for the health care you deserve, please share it with us: [stories@payless.health](stories@payless.health).


Use [act](https://github.com/nektos/act) to test GitHub Actions deployment locally.

## Deployment

Fork this repo, go to settings > pages > source. In the dropdown, select Github Actions.
