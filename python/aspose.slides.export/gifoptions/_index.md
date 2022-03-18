---
title: GifOptions Class
type: docs
weight: 40
url: /python/aspose.slides.export/gifoptions/
---

Represents GIF exporting options.

**Namespace:** [aspose.slides.export](/python/aspose.slides.export/)

**Full Class Name:** aspose.slides.export.GifOptions

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The GifOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|GifOptions()|Initializes a new instance of the GifOptions class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|warning_callback|Returns of sets an object which receives warnings and decides whether loading process will continue or will be aborted.<br/>            Read/write [IWarningCallback](/python/aspose.slides.warnings/iwarningcallback/).|
|progress_callback|Represents a callback object for saving progress updates in percentage.<br/>            See [IProgressCallback](/python/aspose.slides/iprogresscallback/).|
|default_regular_font|Returns or sets font used in case source font is not found.<br/>            Read-write string.|
|frame_size|Gets or sets frame size.|
|export_hidden_slides|Determines whether hidden slides will be exported.<br/>            The default value is false.|
|transition_fps|Gets or sets transition FPS [frames/sec]<br/>            The default value is 25.|
|default_delay|Gets or sets default delay time [ms]. This value will be used if [advance_after_time](/python/aspose.slides/islideshowtransition/) is not set.<br/>            The default value is 1000.|
|as_isave_options|Returns ISaveOptions interface.<br/>            Read-only [ISaveOptions](/python/aspose.slides.export/isaveoptions/).|
