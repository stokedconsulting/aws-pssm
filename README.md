# aws-pssm

Turn .env files into AWS Parameter Store and AWS Secret Manager values for use on production systems and dev environments

![GitHub package.json dynamic](https://img.shields.io/github/package-json/keywords/stokedconsulting/aws-pssm.svg?style=flat-square)

![GitHub](https://img.shields.io/github/license/stokedconsulting/aws-pssm.svg?style=flat-square)
![GitHub package.json version](https://img.shields.io/github/package-json/v/stokedconsulting/aws-pssm.svg?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/stokedconsulting/aws-pssm.svg?style=flat-square)

![GitHub last commit](https://img.shields.io/github/last-commit/stokedconsulting/aws-pssm.svg?style=flat-square)

Includes:

- Not much yet :p

## Usage

### **dev**

`npm run dev`

Runs the CLI application.

You can pass arguments to your application by running `npm run dev -- --your-argument`. The extra `--` is so that your arguments are passed to your CLI application, and not `npm`.

### **clean**

`npm run clean`

Removes any built code and any built executables.

### **build**

`npm run build`

Cleans, then builds the TypeScript code.

Your built code will be in the `./dist/` directory.

### **test**

`npm run test`

Cleans, then builds, and tests the built code.

### **bundle**

`npm run bundle`

Cleans, then builds, then bundles into native executables for Windows, Mac, and Linux.

Your shareable executables will be in the `./exec/` directory.
