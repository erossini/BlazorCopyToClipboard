# CopyToClipboard component for Blazor
![copytoclipboard](https://user-images.githubusercontent.com/9497415/149394222-033ec846-eb5d-4f34-9968-aafb5fc38f96.png)

This is a CopyToClipboard component for [Blazor WebAssembly](https://www.puresourcecode.com/tag/blazor-webassembly/) and [Blazor Server](https://www.puresourcecode.com/tag/blazor-server/) with .NET6.
When the user press the button, the component copies the text in the system clipboard. So, the user can paste the text everywhere else.

For more details about the component, read me [post](https://www.puresourcecode.com/dotnet/blazor/copy-to-clipboard-component-for-blazor/). For support, open your question on my [Forum](https://www.puresourcecode.com/forum/copytoclipboard/).

## Status of the component
The component is a button. When the user press the button the value of the property `Text` is trying to copy this value into the system clipboard.

### Successful copied
If the component had successfully copied the text into the clipboard, the button changes for few seconds its aspect to inform the user the copy had success.
![copytoclipboard-ok](https://user-images.githubusercontent.com/9497415/149396754-e2014f5e-a982-4688-86b6-772e8c62c33c.gif)

### Failed copied
If the component hadn't successfully copied the text into the clipboard, the button changes for few seconds its aspect to inform the user the copy failed.
![copytoclipboard-error](https://user-images.githubusercontent.com/9497415/149396769-e54774e5-83ce-45ae-89aa-dd9847172a77.gif)

## Properties
| Name | Description | Default |
|------|-------------|---------|
| Id   | The component Id. If it is not specified, an new Id wiil be genrated | CopyToClipboard-{GUID} |
| SuccessButtonClass | CSS class for when the text is copied successful in the clipboard | btn btn-success |
| InfoButtonClass | CSS class for the normal state of the button | btn btn-info |
| ErrorButtonClass | This class is used when the component can't copy the text into the system clipboard | btn btn-danger |
| CopyToClipboardText | The text to display on the button | Copy to clipboard |
| CopiedToClipboardText | The text to display when the component successfully copied the text in the system clipboard | Copied to clipboard! |
| ErrorText | The text to display when the component can't copy the text into the system clipboard | Oops. Try again. |
| FontAwesomeCopyClass | Based on [FontAwesome](https://fontawesome.com/) the icon to display for the normal state of the button | fa fa-clipboard |
| FontAwesomeCopiedClass | Based on [FontAwesome](https://fontawesome.com/) the icon to display after the component successfully copied the text into the system clipboard | fa fa-check |
| FontAwesomeErrorClass | Based on [FontAwesome](https://fontawesome.com/) the icon to display when the component had an error to copy the text into the clipboard | fa fa-exclamation-circle |

## Other Blazor components

| Component name | Forum | Description |
|---|---|---|
| [DataTable for Blazor](https://www.puresourcecode.com/dotnet/net-core/datatable-component-for-blazor/) | [Forum](https://www.puresourcecode.com/forum/forum/datatables/) | DataTable component for Blazor WebAssembly and Blazor Server |
| [Markdown editor for Blazor](https://www.puresourcecode.com/dotnet/blazor/markdown-editor-with-blazor/) | [Forum](https://www.puresourcecode.com/forum/forum/markdown-editor-for-blazor/) |  This is a Markdown Editor for use in Blazor. It contains a live preview as well as an embeded help guide for users. |
| [CodeSnipper for Blazor](https://www.puresourcecode.com/dotnet/blazor/code-snippet-component-for-blazor/) | [Forum](https://www.puresourcecode.com/forum/codesnippet-for-blazor/) | Add code snippet in your Blazor pages for 196 programming languages with 243 styles |
| [Copy To Clipboard](https://www.puresourcecode.com/dotnet/blazor/copy-to-clipboard-component-for-blazor/) | [Forum](https://www.puresourcecode.com/forum/copytoclipboard/) | Add a button to copy text in the clipbord | 
| SVG Icons and flags for Blazor | [Forum](https://www.puresourcecode.com/forum/icons-and-flags-for-blazor/) | Library with a lot of SVG icons and SVG flags to use in your Razor pages |
| [Modal dialog for Blazor](https://www.puresourcecode.com/dotnet/blazor/modal-dialog-component-for-blazor/) | [Forum](https://www.puresourcecode.com/forum/forum/modal-dialog-for-blazor/) |  Simple Modal Dialog for Blazor WebAssembly |
| [PSC.Extensions](https://www.puresourcecode.com/dotnet/net-core/a-lot-of-functions-for-net5/) | [Forum](https://www.puresourcecode.com/forum/forum/psc-extensions/) |  A lot of functions for .NET5 in a NuGet package that you can download for free. We collected in this package functions for everyday work to help you with claim, strings, enums, date and time, expressions... |
| [Quill for Blazor](https://www.puresourcecode.com/dotnet/blazor/create-a-blazor-component-for-quill/) | [Forum](https://www.puresourcecode.com/forum/forum/quill-for-blazor/) |  Quill Component is a custom reusable control that allows us to easily consume Quill and place multiple instances of it on a single page in our Blazor application |
| [Segment for Blazor](https://www.puresourcecode.com/dotnet/blazor/segment-control-for-blazor/) | [Forum](https://www.puresourcecode.com/forum/forum/segments-for-blazor/) |  This is a Segment component for Blazor Web Assembly and Blazor Server |
| [Tabs for Blazor](https://www.puresourcecode.com/dotnet/blazor/tabs-control-for-blazor/) | [Forum](https://www.puresourcecode.com/forum/forum/tabs-for-blazor/) |  This is a Tabs component for Blazor Web Assembly and Blazor Server |
| [WorldMap for Blazor]() | [Forum](https://www.puresourcecode.com/forum/worldmap-for-blazor/) | Show world maps with your data |

## More examples and documentation
*   [Write a reusable Blazor component](https://www.puresourcecode.com/dotnet/blazor/write-a-reusable-blazor-component/)
*   [Getting Started With C# And Blazor](https://www.puresourcecode.com/dotnet/net-core/getting-started-with-c-and-blazor/)
*   [Setting Up A Blazor WebAssembly Application](https://www.puresourcecode.com/dotnet/blazor/setting-up-a-blazor-webassembly-application/)
*   [Working With Blazor Component Model](https://www.puresourcecode.com/dotnet/blazor/working-with-blazors-component-model/)
*   [Secure Blazor WebAssembly With IdentityServer4](https://www.puresourcecode.com/dotnet/blazor/secure-blazor-webassembly-with-identityserver4/)
*   [Blazor Using HttpClient With Authentication](https://www.puresourcecode.com/dotnet/blazor/blazor-using-httpclient-with-authentication/)
*   [InputSelect component for enumerations in Blazor](https://www.puresourcecode.com/dotnet/blazor/inputselect-component-for-enumerations-in-blazor/)
*   [Use LocalStorage with Blazor WebAssembly](https://www.puresourcecode.com/dotnet/blazor/use-localstorage-with-blazor-webassembly/)
*   [Modal Dialog component for Blazor](https://www.puresourcecode.com/dotnet/blazor/modal-dialog-component-for-blazor/)
*   [Create Tooltip component for Blazor](https://www.puresourcecode.com/dotnet/blazor/create-tooltip-component-for-blazor/)
*   [Consume ASP.NET Core Razor components from Razor class libraries | Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/core/blazor/components/class-libraries?view=aspnetcore-5.0&tabs=visual-studio)
