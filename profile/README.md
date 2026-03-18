# Atalasoft Support Github

This is the GitHub for [Atalasoft Support](https://www.atalasoft.com/Support).

Atalasoft's flagship product is DotImage Documenet Imaging SDK. This is a .NET (.NET Framework and .NET) Windows Software Development Kit (SDK). 

However, this is a site for our support resources, not really for marketing. If you'd like to know more about what Atalasoft SDKs can do for you, please visit our [products page](https://www.atalasoft.com/Products)


Herein, you will find our public Sample apps / demo repositiories. This is still a work in progress, as we migrate projects in.

Until the switchover is complete, if a demo shows `C# / VB.NET` (with or without links) for the code section, then the repo is live on our GitHub (if VB.NET is missing it may be that we've not gotten to that one yet as we've focused on C# first)

If a demo name link does not have a `C# / VB.net` immeditely following, the link will take you to a slightly older download

You may also find our [full list of current demos](https://www.atalasoft.com/kb2/KB/50086/INFO-Current-Demos-DotImage-WingScan-DotPdf-and-DotTwain-Sample-Applications-Sources) on our Knowledgebase


## Web Demos[](#web)
### HTML 5 WebDocumentViewer (WDV)[](https://www.atalasoft.com/kb2/KB/50086/INFO-Current-Demos-DotImage-WingScan-DotPdf-and-DotTwain-Sample-Applications-Sources#html-5-webdocumentviewer-wdv)

- [WDV Annotation Loader Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/AnnotationLoader.zip) (convenience class for loading WDV annotations)
- [Web Viewing (WDV) Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/WebViewingDemo.zip) (WebDocumentViewer)

### WingScan (Web Capture)

- [WingScan (Web Scanning) Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/WingScanDemo.zip)

### RequireJS (Modularzed) WebDocumentViewer / WebCapture

- [Basic WDV With Require JS](https://atalasupport.net/kb/50393-requireJS/BasicWdv_RequireJS.zip)
- [Basic WebCapture (no Viewer) With Require JS](https://atalasupport.net/kb/50393-requireJS/BasicWebCapture_noViewer_RequireJS.zip)
- [Basic WebCapture (with Viewer) With Require JS](https://atalasupport.net/kb/50393-requireJS/BasicWebCapture_withViewer_RequireJS.zip)

## Desktop (Winforms, Console, and WPF)[](#desktop)
### Newest
A selection of the very newest samples we've created.  

- [HtmlToPdf](https://www.atalasupport.net/demos/ModernDemos-11.5/HtmlToPdf.zip) - A demo showing how to use the new HtmlDecoder and TxtDecoder.

### Minimal Test Harness / Repro Solutions
Samples / Solutions for desktop use for reproducing issues or using as a generic starting point

- [SimpleAtalaConsole](https://github.com/AtalaSupport/SimpleAtalaConsole/wiki) - [C#](https://github.com/AtalaSupport/SimpleAtalaConsole/archive/refs/heads/main.zip) / VB.NET  
    This is a Minimal .NET Framework Console App which is useful as a minimal repro / test harness

### Most Common / Popular

- [Advanced Scan-to-File Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_AdvancedScanToFileDemo_CS_x86) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_AdvancedScanToFileDemo_CS_x86/archive/refs/heads/main.zip) / VB.NET  
  This is a 32 bit demo that shows how to integrate TWAIN scanning with our WinForms DocumentAnnotationViewer control.

- [TWAIN Acquisition Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_TwainAcquisitionDemo_CS_x86) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_TwainAcquisitionDemo_CS_x86/archive/refs/heads/main.zip) / [VB.NET](https://github.com/AtalaSupport/DemoGallery_Desktop_TwainAcquisitionDemo_VB_x86/archive/refs/heads/main.zip)  
    This is a 32 bit demo that shows just DotTwain without any of our viewer objects - its a great best practices for DotTwain.  
    
- [Annotation Viewer Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DocumentAnnotationViewer.zip)  
  The Annotation Viewer Demo (Formerly Document Annotation Viewer Demo) demonstrates how use our DocumentAnnotationViewer control.
  
  This demo should be used to gain a basic understanding of how the DotImage DocumentAnnotationViewer functions.
  
  The demo allows you to open various supported image files, automatically loading any supported embedded annotations. It also allows the creation / editing of various annotation types and saving out the resulting file with annotations being embedded for supported formats. Additionally, it shows the ease of use of the built in undo/redo manager, as well as cut, copy, and paste of annotations, and even full document printing with annotations. Requires DotImage license. Optionally, requires PdfRasterizer license in order to open/read PDF files.

- [Barcode Reader Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_BarcodeReaderDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_BarcodeReaderDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  The Barcode Reader Demo demonstrates how to read a barcode from an image. This demo should be used to gain a basic understanding of how the DotImage Barcode recognition functions. The demo allows you to set options, such as barcode types, scan directions, scan interval and the number of expected barcodes. 
  
  If you are having trouble recognizing a barcode, this demo may help to see why. Requires DotImage and DotImage BarcodeReader. 

- [Document Regions Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_DocumentRegionsDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_DocumentRegionsDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  This is a "Zonal OCR" example. Its actually 2 separate demos: a Creator that gives an example of how to create a Zonal OCR template and a Reader that shows how one might apply the templates.
   
- [DotAnnotate Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_DotAnnotateDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_DotAnnotateDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  This demo shows our AnnotateViewer and the Desktop version of our AnnotationUI classes to read, write and modify annotations on images.  
    
- [DotImage Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_DotImageDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_DotImageDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  The most comprehensive of all the demos demonstrating most of the image processing commands and codecs. This is a good place to learn about the UI features that dotImage offers, as well as testing of image effects, and transforms.   

- [Folder ThumbnailView Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_FolderThumbnailViewDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_FolderThumbnailViewDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  The FolderThumbnailView is a control (derived from the ThumbnailView class) that will display images in a directory as thumbnails. This is useful for displaying the contents of a directory on disk.
  
  The demo shows how the thumbnails can be resized, reordered, and used to show a larger version of the image in the viewer. A background image may also be added to the thumbnails, along with many other features available in the thumbnail control.  
 
- [Office to PDF Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/OfficeToPdf.zip)  
  A sample application to show how to convert office (supported formats such as Word, RTF, PowerPoint, Excel, and MSG) into PDF. This is a very simple console app that converts a Word (.docx or .doc) file into a PDF by using in a memory-efficient way using FileSystemImageSource.
  
  Keep in mind that our support of the older word document format .doc (Word 97 - 2007) is limited. It will work for simpler .doc documents, but for best results, convert your .doc files to the newer .docx (Word 2010 and newer) format first.
  
  Who says you always need a viewer in an imaging application?
  
  This console app uses our FileSystemImageSource to read each frame of the target file directly into a PDF Encoder. Each page read will trigger a Compression Selector event so you can choose the best compression to use for that specific page's Pixel Format.
  
  This approach can easily be adapted to services or plumbed in to batch-based processing.
  
  By setting a handler for PdfEnc.SetEncoderCompression, we are able to dynamically select the most appropriate form of image compression to apply, based on the PixelFormat (color depth) of each page.
   
- [PDF Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_PdfDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_PdfDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Demonstrates how to view and save PDF files with DotImage and DotImage PdfDecoder, as well as our ThumbnailView control. Rasterizes a small thumbnail of each page in the PDF asynchronously while loading the first page in the PDF.
 
- [PdfDocument Combine With Repair](https://www.atalasupport.net/demos/LegacyDemos-11.5/PdfDocumentCombineWithRepair.zip) - C# / VB.NET  
  This is the solution that accompanies our [HOWTO: Combine Multiple PDFs with Automatic Repair of Damaged PDFs](https://www.atalasoft.com/kb2/KB/50071/HOWTO-Combine-Multiple-PDFs-with-Automatic-Repair-of-Damaged-PDFs) KB article.

- [PDF to TIFF Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_PDFtoTIFFDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_PDFtoTIFFDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  A very simple console app that converts a PDF file into a TIFF by using in a memory-efficient and PDF-optimized PdfImageSource and our PdfReader addon.
  
  This console app uses our PdfRasterizer to convert a PDF to a TIFF. This approach can easily be adapted to services or plumbed in to batch-based processing.
  
  By setting a handler for TiffEncoder.SetEncoderCompression, we are able to dynamically select the most appropriate form of image compression to apply, based on the PixelFormat (color depth) of each page. 

- [Searchable PDF (OCR) Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_SearchablePdfDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_SearchablePdfDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  This demo uses our OCR engine to convert an input image (single or multi-page) into a searchable PDF using a GlyphReaderEngine and our PdfTranslator class.
  
  Pre-Processing options (deskewing, border removal, text inversion and line removal) are also provided. 
  
  >**Note:** This sample app is fairly bare-bones, but the concepts covered can easily be applied to your console app, windows service, web service, etc...    
    
- [TIFF to PDF Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_TIFFtoPDFDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_TIFFtoPDFDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Sample app of best practice to convert multi-page TIFF to PDF (but supports other supported single frame formats as well, such as BMP, JPG, PNG, etc...). A very simple console app that converts a TIFF file into a PDF by using in a memory-efficient way using FileSystemImageSource, which is used to read each frame of the target file directly into a PDF Encoder. Each page read will trigger a Compression Selector event so you can choose the best compression to use for that specific page's Pixel Format.
  
  This approach can easily be adapted to services or plumbed in to batch-based processing.
  
  By setting a handler for PdfEnc.SetEncoderCompression, we are able to dynamically select the most appropriate form of image compression to apply, based on the PixelFormat (color depth) of each page.  

- [WPF Annotations Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/WpfAnnotations.zip)  
  This is a WPF application that shows how to use our WPF Annotation Viewer control. The source code should provide a good working example of how yo use our AtalaAnnotationViewer (the WPF version of our AnnotateViewer Windows Forms control) and our annotations in a WPF application .
  
  See below for WPFDemo if you just want a non-annotation-aware WPF Image Viewer.

### Other Demos
Over the years, we had a lot of demos - these are the rest of those classics - kept updated for the latest releases.

- [AdvancedDocClean Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_AdvancedDocCleanDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_AdvancedDocCleanDemo_CS_x64/archive/refs/heads/main.zip)  / VB.NET  
  Demonstrates each of the Document Cleanup and processing commands available in the DotImage Advanced Document Cleanup Module. Shows the before and after images side by side and provides access to each property of each available command. Requires a license of DotImage Document Imaging and DotImage Advanced Document Cleanup to run the compiled demo.  

- [Citrix TWAIN Scanning Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_CitrixScanningDemo_CS_x86) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_CitrixScanningDemo_CS_x86/archive/refs/heads/main.zip) / [VB.NET](https://github.com/AtalaSupport/DemoGallery_Desktop_CitrixScanningDemo_VB_x86/archive/refs/heads/main.zip)  
  TWAIN Scanning under Citrix (and RemoteDesktop) requires a slightly different approach with our DotTwain components. This is a companion solution to our [HOWTO: Scan through Citrix or RDP (Terminal Server)](https://www.atalasoft.com/kb2/KB/50227/HOWTO-Scan-through-Citrix-or-RDP-Terminal-Server) KB article.  

- [ColorExtraction Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_ColorExtractionDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_ColorExtractionDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  This application provides a demonstration of the ColorExtractionCommand included in the Atalasoft DotImage Advanced Document Cleanup module.
  
  This command is used to detect color in a color image, and returns a 32-bit BGRA image with the alpha channel covering the non-color regions. This can be used to determine if a scanned image is actually grayscale, in which case the image can be thresholded to B&W and saved using CCIT or JBIG2 compression, or saved as 8-bit grayscale instead of 24-bit color.  

- [Color Management Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_ColorManagementDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_ColorManagementDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  The Color Management Demo demonstrates how DotImage can use color profiles to display images correctly, and create virtual proofs of images.  

- [CompositeCommand Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_CompositeCommandDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_CompositeCommandDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Shows how to take arbitrary ImageCommands and encapsulate and compose them into one new single ImageCommand. Uses reflection to display all image commands in all referenced assemblies.   

- [CompositePrint Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_CompositePrintDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_CompositePrintDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Demonstrates how to use the ImageCompositePrintDocument class to print multiple images on a single page. This is useful for printing multiple photos or a photo collage. It can be used to conserve expensive photo quality paper by efficiently orienting photos on the paper.   

- [CustomCommand Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_CustomCommandDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_CustomCommandDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  If all you do is run this demo, you'll see that it merely lets you open an image and then flip it horizontally or vertically.  
  
  However, under the hood, you'll see that instead of just using DotImage's built in and very capable FlipCommand class, we're actually doing the work inside CustomFlipCommand.
  
  What is this CustomFlipCommand? It's an example of inheriting our base ImageCommand and using it to build your own. Using the PixelAccessor and PixelMemory classes, we're directly manipulating the underlying pixels that make up the image. What we end up doing is simply rearranging the image, flipping horizontally or vertically... what you do with it is left up to your imagination.
  
  The PixelAccessor and PixelMemory objects are certainly available outside of the ImageCommand structure, but by implementing this as an ImageCommand, you can now use your CustomImageCommand anywhere you would use any of our existing ImageCommand classes.

- [Database Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_DatabaseDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_DatabaseDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Sample of using our DbImageSource class.  

- [Dicom Leveling Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DicomLeveling.zip)  
  Dicom images are specific to the Medical Imaging area, and contain far greater range of brightness / levels than average monitors can show. This demo shows how to traverse various Dicom Levels to see different levels (brightness) of an image.  

- [Dicom Viewer Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DicomViewer.zip)  
  An implementation of our DicomDecoder with an image viewer.  

- [DocumentViewer Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_DocumentViewerDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_DocumentViewerDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Our DocumentViewer Windows Forms viewing control combines a ThumbnailView and WorkspaceViewer into a single control which is designed to prevent common memory issues arising from improper use of the individual controls.  

- [DotPdf Invoice Layout Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DotPdfInvoiceLayout.zip)  
  A simple Invoice layout sample using our PdfGeneratedDocument class.  

- [DotPdf Invoice Shape Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DotPdfInvoiceShape.zip)  
  Creating an "invoice shape" to allow a more advanced Invoice example with PdfGeneratedDocument.  

- [DotPdf Invoice Template Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DotPdfInvoiceTemplate.zip)  
  Using an "Invoice Template" with PdfGeneratedDocument.    

- [DotPdf Shapes Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_DotPdfShapesDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_DotPdfShapesDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  Shapes are a fundamental building block of a Pdf page - Whether the shapes be text or geometric shapes or images. This is a great "getting started with PdfGeneratedDocument" example.  

- [DotPdf Template Generator Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/DotPdfTemplateGenerator.zip)  
  A tool to generate a template for use with PdfGeneratedDocument.  

- [ISIS Scanning Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/IsisDemo.zip)  
  Sample app for using our ISIS scanning. NOTE: this is an x86 example as we do not offer a 64 bit version of the ISIS scanning component.  

- [ISIS Settings Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/IsisSettingsDemo.zip)  
  Sample app for storing and retrieving ISIS scanning settings. NOTE: this is an x86 example as we do not offer a 64 bit version of the ISIS scanning component.  

- [Jpeg2000 Viewer Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/Jp2Viewer.zip)  
  Simple example of using our Jp2Decoder to view Jpeg2000 images.  

- [Levels and Curves Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/LevelsAndCurvesDemo.zip)  
  Levels and Curves applied to images.  

- [Low-Level TWAIN Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/LowLevelTwain.zip)  
  A very low-level example of directly using our TwainController class instead of using the higher level Acquisition class.  

- [Metadata Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/MetadataDemo.zip)  
  Demonstrates how to view, edit, and save metadata in image JPEG, TIFF, RAW, and PNG image files. It includes code that preserves as much metadata as possible when re-saving an image as a TIFF or JPEG. 
  
  The TiffFile class gives the ability to view and edit tiff image metadata without the need to open the image into memory and demonstrates working with arbitrary TIFF tags by embedding an image into the tiff tag. Also demonstrates lossless JPEG features to edit metadata within a JPEG without adding lossy compression artifacts. 
  
  These features requires a license of DotImage Photo Pro or DotImage Document Imaging.  

- [Multipage TIFF Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/MultipageTiffDemo.zip)  
  The Multipage Tiff Demo shows how to view and save multipage Tiff images using the TiffFile class, which allows editing of the image, without the need to open the entire image into memory or the need to re-encode the image data. Some of this functionality includes adding, reordering, or removing pages from the image. The demo also demonstrates many of the Document Imaging functions that are provided with DotImage. 
  
  In addition, this demo makes great use of the ThumbnailView control, displaying all pages in a multipage TIFF in the thumbnail control, as well as allowing the user to reorder and manipulate the individual pages with a nice GUI.

- [Multithread TWAIN Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/MultithreadTwainDemo.zip)  
  Using our TWAIN Acquistion class in a Multithreaded context

- [OCR Diagnostic Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/OcrDiagnostic.zip)  
  "See" an image the way OCR does. Useful for determining what went wrong.

- [OfficeDecoder Text Extraction Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/OfficeDecoderTextExtraction.zip)  
  Using OfficeDecoder to extract text.

- [PdfDoc Simple Repair Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/PdfDocSimpleRepairDemo.zip)  
  Our PdfDocument class offers powerful repair options to fix issues / errors

- [PDF Manipulator Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_PdfManipulatorDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_PdfManipulatorDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  PdfManipulator lets you reorder pages in PDFs via GUI

- [PDF Text Node Extractor](https://www.atalasupport.net/demos/LegacyDemos-11.5/PdfTextNodeExtractor.zip)  
  Extracting text from searchable PDFs

- [PhotoEffect Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/PhotoEffectDemo.zip)  
  Various PhotoEffect classes demonstrated

- [Pig Latin Custom OCR Translator Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/PigLatin.zip)  
  A "fun" implementation of a custom OcrTranslator. In this case, we apply "Pig Latin" rules to English text to emonstratedae igpay atinlay.

- [RawDecoder Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/RawDemo.zip)  
  RawDecoder can handle raw image formats from many digital SLRs and other high end cameras.

- [Simple OCR Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/SimpleOCR.zip)  
  A sample application to show how to use our currently supported OCR Engines

- [ThreadedCommand Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/ThreadedCommandDemo.zip)  
  Taking advantage of multithreading to do heavy image processing

- [TIFF Manipulator Demo](https://github.com/AtalaSupport/DemoGallery_Desktop_TiffManipulatorDemo_CS_x64) - [C#](https://github.com/AtalaSupport/DemoGallery_Desktop_TiffManipulatorDemo_CS_x64/archive/refs/heads/main.zip) / VB.NET  
  TiffManipulator shows how you can use our TiffDocument and ThumbnailView control to make a winforms gui to let you rearrange pages in a tiff and even combine or delete pages.
   
- [TWAIN BarCode Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/TWAINBarCodeDemo.zip)  
  Shows a common scanning use case - separating a single document with barcode (patch) page separators into separate doucments

- [WPF Demo](https://www.atalasupport.net/demos/LegacyDemos-11.5/WpfDemo.zip)  
  A WPF desktop application using AtalaImageViewer (our WPF image viewer similar to WorkspaceViewer on the Winforms side)

## Getting Help for Atalasoft products
Atalasoft regularly updates our support [Knowledgebase](http://www.atalasoft.com/kb2) with the latest information about our products. To access some resources, you must have a valid Support Agreement with an authorized Atalasoft Reseller/Partner or with Atalasoft directly. Use the tools that Atalasoft provides for researching and identifying issues. 

Customers with an active evaluation, or those with active support / maintenance may [create a support case](https://www.atalasoft.com/Support/my-portal/Cases/Create-Case) 24/7, or call in to support ([+1 949 236-6510](tel:19492366510) ) during our normal support hours (Monday - Friday 8:00am to 5:00PM Eastern (New York) time).  

Customers who are unable to create a case or call in may [email our Sales Team](email:sales@atalasoft.com).  

