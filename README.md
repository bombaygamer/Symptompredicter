
## Description

The  Medical Symptom Checker is designed to help you understand the possible causes of symptoms in children and adults.

## Mission

Our mission is to create a free and open source medical symptom checker where all doctors and developers can contribute to it.


## Features

- Well-constructed medical symptom checker.
- Responsive.
- Accessible.
- Beginner-friendly.
- Intuitive interface.
- Valid source codes.

## Data Sources

You can find the data sources of the symptoms and diseases at:

- **src/data/SymptomName.jsx**
- **src/data/DiseaseSymptoms.jsx**

## Build Instructions

1. Navigate to the **src/** directory using your terminal.
2. Run the following commands:

```
npm install
npm run build
```

3. Test the app locally or online using a live server.

**Note:** If you are testing the app in a subdirectory, make sure to tune the base URL correctly before testing.

## GitHub Pages Deployment Instructions

If you wish to deploy your forked version to GitHub, follow the instructions below.

1. Edit the "package.json" file by adding the following line after the "name" declaration:

```
"homepage": "https://{GITHUB_USERNAME}.github.io/{REPOSITORY_NAME}/",
```

> Note: Replace {GITHUB_USERNAME} with your GitHub username and {REPOSITORY_NAME} with your repository name.

2. Install "gh-pages":

```
npm install gh-pages --save-dev
```

3. Deploy the app:

```
npm run deploy
```

## Contribution

We welcome all developers and doctors to contribute to this repository by adding features or fixing bugs. The source codes will always be free and open source.


