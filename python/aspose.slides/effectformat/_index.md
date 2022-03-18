---
title: EffectFormat Class
type: docs
weight: 450
url: /python/aspose.slides/effectformat/
---

Represents effect properties of shape.

**Namespace:** [aspose.slides](/python/aspose.slides/)

**Full Class Name:** aspose.slides.EffectFormat

**Assembly:**  Aspose.Slides Version: 22.1.0.0

The EffectFormat type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|as_ipresentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/python/aspose.slides/ipresentationcomponent/).|
|is_no_effects|Returns true if all effects are disabled (as just created, default EffectFormat object).<br/>            Read-only bool.|
|blur_effect|Blur effect.<br/>            Read/write [IBlur](/python/aspose.slides.effects/iblur/).|
|fill_overlay_effect|Fill overlay effect.<br/>            Read/write [IFillOverlay](/python/aspose.slides.effects/ifilloverlay/).|
|glow_effect|Glow effect.<br/>            Read/write [IGlow](/python/aspose.slides.effects/iglow/).|
|inner_shadow_effect|Inner shadow.<br/>            Read/write [IInnerShadow](/python/aspose.slides.effects/iinnershadow/).|
|outer_shadow_effect|Outer shadow.<br/>            Read/write [IOuterShadow](/python/aspose.slides.effects/ioutershadow/).|
|preset_shadow_effect|Preset shadow.<br/>            Read/write [IPresetShadow](/python/aspose.slides.effects/ipresetshadow/).|
|reflection_effect|Reflection. <br/>            Read/write [IReflection](/python/aspose.slides.effects/ireflection/).|
|soft_edge_effect|Soft edge.<br/>            Read/write [ISoftEdge](/python/aspose.slides.effects/isoftedge/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/python/aspose.slides/ibaseslide/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/python/aspose.slides/ipresentation/).|
|as_ieffect_param_source|Allows to get base IEffectParamSource interface.<br/>            Read-only [IEffectParamSource](/python/aspose.slides/ieffectparamsource/).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|set_blur_effect(radius, grow)|Sets blur effect.|
|enable_fill_overlay_effect()|Enables fill overlay effect.|
|enable_glow_effect()|Enables glow effect.|
|enable_inner_shadow_effect()|Enables inner shadow effect.|
|enable_outer_shadow_effect()|Enables outer shadow effect.|
|enable_preset_shadow_effect()|Enables preset shadows effect.|
|enable_reflection_effect()|Enables reflection effect.|
|enable_soft_edge_effect()|Enables soft edge effect.|
|disable_blur_effect()|Disables blur effect.|
|disable_fill_overlay_effect()|Disables fill overlay effect.|
|disable_glow_effect()|Disable glow effect.|
|disable_inner_shadow_effect()|Disables inner shadow effect.|
|disable_outer_shadow_effect()|Disables outer shadow effect.|
|disable_preset_shadow_effect()|Disables preset shadow effect.|
|disable_reflection_effect()|Disables reflection effect.|
|disable_soft_edge_effect()|Disables soft edge effect.|
|get_effective()|Gets effective effect formatting data with the inheritance applied.|
