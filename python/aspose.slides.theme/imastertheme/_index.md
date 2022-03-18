---
title: IMasterTheme Class
type: docs
weight: 280
url: /python/aspose.slides.theme/imastertheme/
---

Represents a master theme.

**Namespace:** [aspose.slides.theme](/python/aspose.slides.theme/)

**Full Class Name:** aspose.slides.theme.IMasterTheme

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The IMasterTheme type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|extra_color_schemes|Returns the collection of additional color schemes.<br/>            These schemes don't affect presentation's look, they can be selected as main color scheme for a slide.<br/>            Read-only [IExtraColorSchemeCollection](/python/aspose.slides.theme/iextracolorschemecollection/).|
|name|Returns the name of a theme.<br/>            Read/write string.|
|as_itheme|Allows to get base ITheme interface.<br/>            Read-only [ITheme](/python/aspose.slides.theme/itheme/).|
|color_scheme|Returns the color scheme.<br/>            Read-only [IColorScheme](/python/aspose.slides.theme/icolorscheme/).|
|font_scheme|Returns the font scheme.<br/>            Read-only [IFontScheme](/python/aspose.slides.theme/ifontscheme/).|
|format_scheme|Returns the shape format scheme.<br/>            Read-only [IFormatScheme](/python/aspose.slides.theme/iformatscheme/).|
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_effective()|Gets effective theme data with the inheritance applied.|
