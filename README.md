# Port to VS 2013, .NET 4.5, and [MonoGame](http://www.monogame.net/)

As XNA ceased to exist and the [From glyph recognition to augmented reality](https://www.codeproject.com/Articles/258856/From-glyph-recognition-to-augmented-reality) article at CodeProject still looked interesting to me I've decided to port the project into VS 2013 using MonoGame port of XNA.

The port went smoothly and the only trouble I had when replacing XNA Microsoft.Xna.Framework.Graphics.GraphicsDevice.Present() method having 3 parameters with the MonoGame Present() method having no parameters at all. For now I’ve just tested that the app continued working after this blind replacement, later on I have to take a look at specifics.

## References

[From glyph recognition to augmented reality](https://www.codeproject.com/Articles/258856/From-glyph-recognition-to-augmented-reality)

[andrewkirillov/gratf](https://github.com/andrewkirillov/gratf)
