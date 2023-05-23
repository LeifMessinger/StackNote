# StackNote
Track your sidenotes/footnotes/tangents using a stack.

This is in very heavy development. At the moment, I'm using XML. Really, the beginning and ending tags like `<TangentName> </TangentName>` are just `push("Tangent Name") pop()`. That's one reason why xml is bad. I can't do tag names with spaces, but I could do `<Tangent name="with spaces">`.
