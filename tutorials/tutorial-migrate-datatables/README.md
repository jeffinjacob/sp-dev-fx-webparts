# Tutorial: Migrate jQuery and DataTables solution built using Script Editor Web Part to SharePoint Framework

Sample jQuery DataTables solution migrated from a Script Editor Web Part to the SharePoint Framework.

![jQuery DataTables solution built using Script Editor Web Part](https://devofficecdn.azureedge.net/sharepointdocumentation/images/datatables-sewp.png)

Sub folders represent the different stages of the migration process. Each folder contains the complete solution that you can run in browser. More information about the solution is available at [https://docs.microsoft.com/sharepoint/dev/spfx/web-parts/guidance/migrate-jquery-datatables-script-to-spfx](https://docs.microsoft.com/sharepoint/dev/spfx/web-parts/guidance/migrate-jquery-datatables-script-to-spfx).

| Folder | Stage | More information
| ------------- | ------------- | ------------- |
| 01-migrated-sewp-to-spfx | Original solution migrated to SPFx. As much as possible of the original code left unaltered | [details](https://docs.microsoft.com/sharepoint/dev/spfx/web-parts/guidance/migrate-jquery-datatables-script-to-spfx)
| 02-added-configuration | Extended the code with support for configuring the web part through the property pane | [details](https://docs.microsoft.com/sharepoint/dev/spfx/web-parts/guidance/migrate-jquery-datatables-script-to-spfx#add-support-for-configuring-the-web-part-through-web-part-properties)
| 03-transformed-js-to-typescript | Transformed plain JavaScript to TypeScript | [details](https://docs.microsoft.com/sharepoint/dev/spfx/web-parts/guidance/migrate-jquery-datatables-script-to-spfx#transform-the-plain-javascript-code-to-typescript)


# Compatibility

![SPFx 1.10](https://img.shields.io/badge/SPFx-1.10.0-green.svg) 
![Node.js v10 | v8](https://img.shields.io/badge/Node.js-v10%20%7C%20v8-green.svg) 
![Compatible with SharePoint Online](https://img.shields.io/badge/SharePoint%20Online-Compatible-green.svg)
![Does not work with SharePoint 2019](https://img.shields.io/badge/SharePoint%20Server%202019-Incompatible-red.svg)
![Does not work with SharePoint 2016 (Feature Pack 2)](https://img.shields.io/badge/SharePoint%20Server%202016%20(Feature%20Pack%202)-Incompatible-red.svg "SharePoint Server 2016 Feature Pack 2 requires SPFx 1.1")
![Local Workbench Compatible](https://img.shields.io/badge/Local%20Workbench-Compatible-green.svg)
![Hosted Workbench Compatible](https://img.shields.io/badge/Hosted%20Workbench-Compatible-green.svg)

## Applies to

* [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Microsoft 365 developer tenant](https://docs.microsoft.com/sharepoint/dev/spfx/set-up-your-developer-tenant)

## Solution

Solution  | Author(s)
------------- | -------------
tutorial-migrate-datatables  | Waldek Mastykarz (MVP, [Rencore](https://rencore.com), @waldekm) & Andrew Connell (MVP, [Voitanos](//github.com/voitanos), [@andrewconnell](//github.com/andrewconnell))

## Version history

Version | Date            | Comments
--------| --------------- | --------
1.0.0   | June 27, 2017   | Initial commit
1.1.0   | June 28, 2017   | Updated tutorial code for SPFx v1.10

## Build and run the tutorials

To build and run this client-side project, you will need to clone and build the tutorials project. Because the solution retrieves its data from SharePoint, you will also need a custom list named **IT Requests** with some data in it. To preview the web part use the hosted version of the SharePoint Workbench loaded in the context of the site where the Tasks list is located.

Clone this repo by executing the following command in your console:

```console
git clone https://github.com/pnp/sp-dev-fx-webparts.git
```

Navigate to the cloned repo folder which should be the same as the repo name:

```console
cd sp-dev-fx-webparts
```

Navigate to the `tutorials-migrate-datatables` folder:

```console
cd tutorials
```

Navigate to the `specific web part` folder:

```console
cd 'subfolder'
```

Now run the following command to install the npm packages:

```console
npm install
```

This will install the required npm packages and dependencies to build and run the SharePoint Framework project.

Once the npm packages are installed, run the command to preview your web parts in SharePoint Workbench:

```console
gulp serve --nobrowser
```

## Disclaimer

**THIS CODE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

----------

<img src="https://pnptelemetry.azurewebsites.net/sp-dev-fx-webparts/tutorial-migrate-datatables" />
