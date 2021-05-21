---
title: Java Font Management API - Aspose 
weight: 40
url: /java/ 
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="Java APIs to Manipulate Fonts" h2="Aspose.Font" logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/header/aspose_font-for-java.png" pfName="" subTitlepfName="" downloadUrl="https://downloads.aspose.com/font/java" >}}

{{< blocks/products/pf/main-container pfName="" subTitlepfName="" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/272x272/aspose_font-for-java.png" liveDemosLink="" PricingLink="https://purchase.aspose.com/pricing/font/java" buyLink="https://purchase.aspose.com" docsLink="https://docs.aspose.com/font/java/release-notes/" instalationsDocsLink="https://docs.aspose.com/font/java/installation/" nugetLink="" nugetPackageName="" >}}

{{< blocks/products/pf/tab-content >}}
{{< /blocks/products/pf/tab-content >}}

<!--Diagrams Start-->
{{< blocks/products/pf/carousel >}}

{{< blocks/products/pf/carousel-item h3="" description="" >}}
{{< /blocks/products/pf/carousel-item >}}

{{< /blocks/products/pf/carousel >}}
<!--Diagrams End-->

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray singleproduct">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="h2title">
    Advanced Java Font Management API Features
   </h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-upload ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Load font documents from disk
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-repeat ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Load font files stream
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-pencil-square-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Read font information
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-floppy-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Save updated font files to disk
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-book ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Read Glyphs and Metrics information
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-search ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Detect Latin Symbols in Fonts
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-certificate ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Extract embedded licensing information
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-flag ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Render text using font glyphs
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-cogs ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Support different font formats
    </p>
   </div>
   <!--<div class="col-lg-12">

<h2 class="h2title">Latest PUB API Features</h2>

<p>Aspose.PUB for .NET API continuously adding more features to make it powerful. Here is list of few picks from the latest ones added.</p>

<ul>

<li>Support of Fill layers. Pattern, Color and Gradient fill</li>

<li>Support of GdFlResource, VmskResource, PtFlResource and VsmsResource</li>

<li>Load JPEG/PNG/etc image files to PsdImage without direct loading</li>

<li>Support of Layer Vector Masks and Text Layer Custom FlipRotate</li>

<li>Rendering of Stroke effect with Color Fill for export</li>

</ul>

</div>-->
   <div class="col-lg-12">
    <h2 class="h2title">
     Load, Extract and Save TrueType Font
    </h2>
    <p>
     Aspose.Font for Java can easily load, extract and save different font formats. Here is just few lines of code for TrueType TTF.
    </p>
    <div class="codeblock" id="code">
     <h3>
      Load, Extract and Save TTF - Java
     </h3>
     <pre><code class="cs">byte[] fontMemoryData = Utils.getInputFileBytes("Montserrat-Regular.ttf");



 //Font file name with full path

FontDefinition fd = new FontDefinition(FontType.TTF, new FontFileDefinition("ttf", new ByteContentStreamSource(fontMemoryData)));

TtfFont font = (TtfFont) Font.open(fd);



//Work with data from just loaded TtfFont object



//Save TtfFont to disk

font.save(Utils.getDataDir() + "Montserrat-Regular_out.ttf");</code></pre>
    </div>
   </div>
   <!--<div class="col-lg-12">

<h2 class="h2title">Access & Manipulate PUB Layers</h2>

<p>Aspose.PUB for .NET lets you access layers of a PUB with the ability to draw on it with either image or text. You can merge layers, update text on layers, set effects or export layer as an image. You may also use PUB .NET API to detect flattened PUB files or create thumbnails.</p>

</div>-->
   <!--<div class="col-lg-12">

<h2 class="h2title">Read or Create PUB Files</h2>

<p>Aspose.PUB for .NET not only supports loading PSD & PSB file formats for manipulation & conversion but it also provides the capability to create PUB & PSB files from scratch. .NET developers can use the API to automate scenarios that may help them on their way.</p>

<div id="code" class="codeblock">

<h3>Create PUB from scratch - C#</h3>

<pre><code class="cs">using (var PUB = Aspose.PSD.Image.Create(new Aspose.PSD.ImageOptions.PsdOptions()

{

    Source = new Aspose.PSD.Sources.FileCreateSource(dir + "output.psd", false),

    ColorMode = Aspose.PSD.FileFormats.Psd.ColorModes.Rgb,

    CompressionMethod = Aspose.PSD.FileFormats.Psd.CompressionMethod.RLE,

    Version = 4

}, 400, 400))

{

    // draw some graphics over the newly created PSD

    var graphics = new Aspose.PSD.Graphics(psd);

    graphics.Clear(Aspose.PSD.Color.White);

    graphics.DrawEllipse(new Aspose.PSD.Pen(Aspose.PSD.Color.Red, 6), new Aspose.PSD.Rectangle(0, 0, 400, 400));

    psd.Save();

}</code></pre>

</div>

</div>-->
   <!--<div class="col-lg-12">

<h2 class="h2title">Various Imaging Filters</h2>

<p>Aspose.PUB for .NET provides the core imaging features such as color adjustment via its class libraries. Developers can easily adjust brightness, contrast or gamma on raster image loaded by the API. Furthermore, developers can dynamically dither or blur images as well as use popular filters including Median, Gauss Wiener, Motion Wiener and Bradley Threshold.</p>

</div>-->
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/testimonials title="" subTitle="" >}}

{{< blocks/products/pf/testimonials-quote >}}
{{< /blocks/products/pf/testimonials-quote >}}

{{< /blocks/products/pf/testimonials >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/font/java" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-font/Aspose.Font-for-Java" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/font/java" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/font" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Font for Java?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/font/java" pricingInformationLink="https://purchase.aspose.com/pricing/font/java" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.Font offers individual Font processing APIs for other popular development environments as listed below:" >}}

    {{< blocks/products/pf/offers-section-item link="/font/net" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/272x272/aspose_font-for-net.png" sdkName="Aspose.Font for .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/font/cpp" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/272x272/aspose_font-for-cpp.png" sdkName="Aspose.Font for C++" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}