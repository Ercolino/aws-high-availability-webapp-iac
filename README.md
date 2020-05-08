# Deploy a high-availability web app using CloudFormation.

This is the second project of the Udacity Nanodegree Program "Cloud Dev Ops Engineer".
The goal was running a high available web app using Infrastructure as Code.

You can take a look in the infrastructure diagram [here](diagram/aws_high_availability_webapp.png).

### Preconfig

You need to install **[AWS CLI](https://aws.amazon.com/cli/)**.

Then configure it like the following example:

```
$ aws configure
AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
Default region name [None]: us-west-2
Default output format [None]: json
```

### Help scripts

Run this commands ...

- to create a stack:

```
./scripts/create.sh <STACK_NAME> <YML TEMPLATE> <JSON PARAMETERS FILE>
```

- to update a stack:

```
./scripts/create.sh <STACK_NAME> <YML TEMPLATE> <JSON PARAMETERS FILE>
```

-to delete a stack:

```
./scripts/delete.sh <STACK_NAME>
```

### How to access the deployed website

An output is provided with the Website URL