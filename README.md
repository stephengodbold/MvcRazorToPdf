#MvcRazorToPdf
Create pdf documents within an asp .net mvc project by generating your views as normal but returning a PdfActionResult.

##Important Note

The iText library used is licensed under AGPL. This license permits you to use the library for free, if you open source your code. It also contains a CopyLeft clause, meaning it applies to all consuming libraries. If you choose to use this (MvcRazorToPdf) library in a closed source, commercial application you will need to license iText appropriately. Please see http://itextpdf.com/Pricing for more details.

*Demo link to follow

This converts regular produced razor/html to pdf documents in the browser using the iTextXmlWorker.

This uses the newer version/licence of iText/iTextXmlWorker and can process the html that is produced from your views.

##Installation instructions:

Run the following nuget command from your mvc project to install the [package] (http://nuget.org/packages/MvcRazorToPdf/):

`Install-Package MvcRazorToPdf`

##How to use it
1. Create a shared layout that is compatible with an iTextXmlWorker document [Simple example layout] (https://github.com/andyhutch77/MvcRazorToPdf/blob/master/MvcRazorToPdfExample/Views/Shared/_PdfLayout.cshtml)
2. Create a controller action that return a PdfActionResult (model optional) [Simple example contoller] (https://github.com/andyhutch77/MvcRazorToPdf/blob/master/MvcRazorToPdfExample/Controllers/PdfController.cs)
3. Create the view page to render as normal [Simple example view] (https://github.com/andyhutch77/MvcRazorToPdf/blob/master/MvcRazorToPdfExample/Views/Pdf/Index.cshtml)

[Complete example project] (https://github.com/andyhutch77/MvcRazorToPdf/tree/master/MvcRazorToPdfExample)

##Useful info

[iTextXmlWorker docs] (http://demo.itextsupport.com/xmlworker/itextdoc/flatsite.html).
[http://demo.itextsupport.com/xmlworker/] (http://demo.itextsupport.com/xmlworker/) if you have problems getting certain styles to render.

TO FINISH

