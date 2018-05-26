# zrender for sciter
zrender for sciter

# version
zrender version: 4.0.4  
sciter minimum version: 4.1.8.5918

# known unsupported features
1. SVG/VML canvas  
2. Image pattern brush  
3. Path stroke(border) hit-test (processing) 
4. zrImage (processing)
5. CanvasRadialGradient only supports one center point
6. CanvasRenderingContext2D::globalAlpha (affected: style::alpha)
7. CanvasRenderingContext2D::globalCompositeOperation (affected: style::blend)
8. CanvasRenderingContext2D::miterLimit (affected: style::miterLimit)

# renamed
1. Element -> zrElement (Element.tis)
2. Storage -> zrStorage (Storage.tis)
3. ZImage -> zrImage (graphics/Image.tis)
4. assert -> assertf (core/util.tis)
5. TransitionObject::property -> prop (graphics/States.tis)
6. Transformable::getLocalTransform -> getLocalTransform2 (mixin/Transformable.tis)

# original project
https://github.com/ecomfe/zrender
