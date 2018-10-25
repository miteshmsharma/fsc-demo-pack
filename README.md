# Financial Services Cloud (FSC) Demo Pack

This repository contains an [AppExchange Demo Kit (ADK) Recipe](config/demo-recipe.json) and some carefully crafted [App Config](mdapi-source/app-config) and [Data Config](mdapi-source/data-config) Salesforce metadata.  Collectively, these can be used by anyone with the [SFDX-Falcon Plugin](https://github.com/sfdx-isv/sfdx-falcon) to build a fully-functional Financial Services Cloud (FSC) demo in a Scratch Org in **8 minutes or less** with _zero_ manual steps. 

**Here's what that looks like:**

![AppExchange Demo Kit (ADK) falcon:demo:install](https://drive.google.com/uc?export=view&id=1pHTCkPSmGHzS_FoqidyA400ys6yFV8Am)

## How to Install the FSC Demo Pack

Salesforce Developers, Administrators, Business Analysts, and anyone else with a [Salesforce Developer Hub](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_enable_devhub.htm) and the [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli) can have an FSC demo org up and running in 8 minutes or less!

Just follow the [SFDX-Falcon Quick Start Guide](https://sfdx-isv.github.io/sfdx-falcon/start/quickstart.html), then execute three simple commands:

```html
$ sfdx falcon:demo:clone https://github.com/sfdx-isv/fsc-demo-pack.git

$ cd fsc-demo-pack

$ sfdx falcon:demo:install
```

## Questions / Comments?

To report bugs or request new features for the FSC Demo Pack, [create an issue in this repository](https://github.com/sfdx-isv/fsc-demo-pack/issues). 

Additional support is available to Salesforce ISV Partners via the [SFDX-Falcon Chatter Group](http://bit.ly/sfdx-falcon-group) in the Salesforce Partner Community.

## Acknowledgements

The FSC Demo Pack was built by [Vivek M. Chawla](https://twitter.com/VivekMChawla) with contributions from [Jaswinder Rattanpal](https://twitter.com/jrattanpal) and [Danny Chang](https://twitter.com/DannySFDC).

The [SFDX-Falcon Plugin](https://github.com/sfdx-isv/sfdx-falcon) and the [AppExchange Demo Kit](https://github.com/sfdx-isv/sfdx-falcon-appx-demo-kit) were created by [Vivek M. Chawla](https://twitter.com/VivekMChawla). 

## License

The **FSC Demo Pack**, **SFDX-Falcon**, and the **AppExchange Demo Kit (ADK)**, are made available under the MIT License. See the [LICENSE](LICENSE) file for details.