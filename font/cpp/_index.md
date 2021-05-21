---
title: C++ Font Integration and Processing API - Aspose 
weight: 20
url: /cpp/ 
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="C++ Font Manipulation Library" h2="Aspose.Font" logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/header/aspose_font-for-cpp.png" pfName="" subTitlepfName="" downloadUrl="https://downloads.aspose.com/font/cpp" >}}

{{< blocks/products/pf/main-container pfName="" subTitlepfName="" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/272x272/aspose_font-for-cpp.png" liveDemosLink="" PricingLink="https://purchase.aspose.com/pricing/font/cpp" buyLink="https://purchase.aspose.com" docsLink="https://docs.aspose.com/font/cpp/release-notes/" instalationsDocsLink="https://docs.aspose.com/font/cpp/installation" nugetLink="https://www.nuget.org/packages/Aspose.Font.Cpp/" nugetPackageName="Aspose.Font.Cpp" >}}

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
    Advanced C++ Font Management API Features
   </h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-upload ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Load font documents from disc
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
     Save updated font files to disc
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
     Support various font formats
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
     Aspose.Font for C++ can easily load, extract, and save TrueType font formats. Here are just few lines of code for TrueType TTF.
    </p>
    <div class="codeblock" id="code">
     <h3>
      Load, Extract and Save TTF - C++
     </h3>
     <pre><code class="cs">//byte array to load Font from

System::ArrayPtr fontMemoryData = System::IO::File::ReadAllBytes(dataDir + u"Montserrat-Regular.ttf");

System::SharedPtr fd = System::MakeObject(Aspose::Font::FontType::TTF, System::MakeObject(u"ttf", System::MakeObject(fontMemoryData)));

System::SharedPtr ttfFont = System::DynamicCast_noexcept(Aspose::Font::Font::Open(fd));

    

//Save CffFont to disk

//Output Font file name with full path

System::String outputFile = RunExamples::GetDataDir_Data() + u"Montserrat-Regular_out.ttf";

ttfFont-&gt;Save(outputFile);</code></pre>
    </div>
   </div>
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
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/font/cpp" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-font/Aspose.Font-for-C" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/font/cpp" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/font" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/font/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Font for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/font/cpp" pricingInformationLink="https://purchase.aspose.com/pricing/font/cpp" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.font offers individual Font management APIs for other popular development environments as listed below:" >}}

    {{< blocks/products/pf/offers-section-item link="/font/net" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/font/272x272/aspose_font-for-net.png" sdkName="Aspose.Font for .NET" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}