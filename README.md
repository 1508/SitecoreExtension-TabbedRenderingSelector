SitecoreExtension-TabbedRenderingSelector
=======================================
Sitecore Shell Override that Adds Tabs to the Select Rendering based on the rendering folder structure.

Overrides the default Select Rendering Shell with a tabbed view. 
Based on blog post by Kacper Chomicz, Software Engineer at cognified
http://www.cognifide.com/blogs/sitecore/sitecore-tabbed-select-a-rendering-dialog/
			
Requires Sitecore 6.x.

Now available on nuget and github.

1508 / Design in Love with Technology / http://1508.dk

## Requirements
* Sitecore 6.x 

## Installation 
Install via nuget
<pre>
  PM> Install-Package SitecoreExtension.TabbedRenderingSelector
</pre>

Please notice that the Sitecore folder gets added to you project because nuget copies on Override xml file to Sitecore Shell Override, it is a feature of Nuget packages and you may contribute a fix if you have a pretty init.ps model e.g.. 

## How it works 
The code is activated with the SelectRendering.xml that is copied to sitecore\shell\Override and lets you override default Sitecore renderings.

The tab structure is based on the folder structure of the renderings folder. 