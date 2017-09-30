# FontoBene

FontoBene is a vector font format. It only uses strokes to form glyphs, in
order for easy rendering in systems that cannot easily deal with more complex
parts of formats like TTF or OTF (e.g. Bézier curves).

FontoBene was designed with the use case of text on printed circuit boards
(PCBs) in mind. PCBs are usually manufactured using the Gerber format as an
exchange format to describe the etching layers, which does not support
quadratic / cubic curves.

You can find the current version of the specification at
[SPECIFICATION.md](SPECIFICATION.md).

**The specification is still work in progress. It will be stabilized in the
coming weeks, together with a formal grammar and a reference implementation.**
