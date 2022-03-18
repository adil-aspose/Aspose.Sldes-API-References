---
title: ITiffOptions Class
type: docs
weight: 340
url: /python/aspose.slides.export/itiffoptions/
---

Provides options that control how a presentation is saved in TIFF format.

**Namespace:** [aspose.slides.export](/python/aspose.slides.export/)

**Full Class Name:** aspose.slides.export.ITiffOptions

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The ITiffOptions type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|image_size|Specifies size of a generated TIFF image.<br/>            Default value is 0x0, what means that generated image sizes will be calculated based on presentation slide size value.<br/>            Read/write aspose.pydrawing.Size.|
|dpi_x|Specifies the horizontal resolution in dots per inch.<br/>            Read/write int.|
|dpi_y|Specifies the vertical resolution in dots per inch.<br/>            Read/write int.|
|show_hidden_slides|Specifies whether the generated document should include hidden slides or not.<br/>            Default is|
|compression_type|Specifies the compression type.<br/>            Read/write [TiffCompressionTypes](/python/aspose.slides.export/tiffcompressiontypes/).|
|pixel_format|Specifies the pixel format for the generated images.<br/>            Read/write [ImagePixelFormat](/python/aspose.slides.export/imagepixelformat/).|
|notes_comments_layouting|Provides options that control how notes and comments is placed in exported document.|
|as_isave_options|Returns ISaveOptions interface.<br/>            Read-only [ISaveOptions](/python/aspose.slides.export/isaveoptions/).|
|warning_callback|Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [IWarningCallback](/python/aspose.slides.warnings/iwarningcallback/).|
|progress_callback|Represents a callback object for saving progress updates in percentage. <br/>            See [IProgressCallback](/python/aspose.slides/iprogresscallback/).|
|default_regular_font|Returns or sets font used in case source font is not found.<br/>            Read-write string.|
