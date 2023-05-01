# Welcome to your Multi Environment Deployments project Using AWS CDK TypeScript 
This is a multi environment deployments project for CDK development with TypeScript.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## URLs

Git Repo: 

AWS Profile NPM Package: https://www.npmjs.com/package/awsprofile

Git Branch NPM Package: https://www.npmjs.com/package/git-branch

AWS CDK Feature Flags: https://docs.aws.amazon.com/cdk/v2/guide/featureflags.html

AWS CDK Documentation: https://docs.aws.amazon.com/cdk/api/v2/docs/aws-construct-library.html

## Commands

### CDK Bootstrap

```
cdk bootstrap aws://accountnumber/ap-southeast-2
```

### CDK Initialization

```
cdk init app --language=typescript
```

### Git Branch Install

```
npm i git-branch
npm i -D @types/git-branch
```

### CDK Commands

```
cdk list          # List CDK Stacks
cdk synth         # Synthesize CDK project to generate CFN template
cd deploy         # Deploy CDK project
```

### Git Commands

```
git add -A && git commit -m "Pushing infrastructure to develop"
git push -u origin develop

git checkout main
git merge develop
git push -u origin main
```