> See the details on how to publish content on the internal documentation page.

## **Docusaurus**

[**Docusaurus**](https://docusaurus.io/) is a static site generator from Meta Open Source, made exclusively for creating documentation sites. It is the tool used at StackSpot.

## **What benefits does the tool offer?**

- The documentation team used Hugo before, but it was different from what the team needed now. We wanted to maintain the doc as code and be more collaborative. We needed to improve the design system, so we chose this tool.
- Docusaurus is made with React. It makes improving the documentation UI and using Citric (StackSpot's Design System) easier.
- It uses MD.
- The website's search feature is from Algolia, which improves the user experience, where they can find the right pages with the words they want.
- Internationalization: You can easily add several languages.

## **Docusaurus Guide**

### Installing

#### Requirements

- [**Node.js**](https://nodejs.org/en/download/) version 16.14 or higher (check by running the **`node -v`** command).

- You can use [**nvm**](https://github.com/nvm-sh/nvm) to manage multiple versions of Node.  

> When you install Node.js, check all the dependencies options.

Follow the steps below:

### **Step 1. Clone the internal documentation repository**

```bash
git clone https://github.com/stack-spot/stackspot-internaldocs
```

### **Step 2. Install [**Docusaurus**](https://docusaurus.io/)**

Execute the command below:

```bash
npm start
```

### Step 3. Install [**Node.js**](https://nodejs.org/en/download/)

To check if it's working, execute the command below:

```bash
node -v
```

### **Local Development**

```bash
npm start
```

Or:

"`bash
npx docusaurus start
```

This command shows the local development server.

- A new page opens in your browser;
- Go to the page you are working on. You can see your changes.

## Publish Content

TBD
