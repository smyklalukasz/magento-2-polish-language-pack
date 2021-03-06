# How to contribute Polish Language pack

In this tutorial, I will show you how to contribute Polish language pack

## Step 1: Download 

First of all, you should fork the repo. In the top-right corner of the page, click **Fork**.
![fork](https://help.github.com/assets/images/help/repository/fork_button.jpg)


## Step 2: Update github_contributions.csv

Let's me explain the workflow:

- This file [crowdin_pull.csv](https://github.com/mageplaza/magento-2-polish-language-pack/blob/master/crowdin_pull.csv) has been pulled from [Crowdin](https://crowdin.com/project/magento-2) daily, so you should not change/edit the file.

- [github_contributions.csv](https://github.com/mageplaza/magento-2-polish-language-pack/blob/master/github_contributions.csv) has been contributed by Mageplaza community.

- We will merge two files: crowdin_pull.csv and github_contributions.csv into [pl_PL.csv](https://github.com/mageplaza/magento-2-polish-language-pack/blob/master/pl_PL.csv). Your Magento 2 store will use this csv file.

So, you should contribute to `github_contributions.csv` file.

### How to edit file github_contributions.csv

The `github_contributions.csv` is saparated **line by line**, see:

```
"Create Order","Crear pedido",module,Magento_AdvancedCheckout
```

- "Create Order": Original string
- "Crear pedido": Translated string
- module: declare module syntax
- Magento_AdvancedCheckout: module scope (only translate in this module)


Fom the begining, `github_contributions.csv` is empty, you guys should add more translations into it.

#### Suggest
- You can copy apart of `crowdin_pull.csv` into `github_contributions.csv` then translate them.

## Step 3: Contribute

- Now time to contribute, **commit your work** to this repo.
- After commit, it will ask you to create a pull request, so please create pull request then will check and approve it.

You can [install this language package via composer](https://github.com/mageplaza/magento-2-polish-language-pack#-method-1-composer-method-recommend) and other people can install / contribute this language pack.

Happy translating!


