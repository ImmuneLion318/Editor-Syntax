## Editor-Syntax

Usages 
```csharp
/* Call On Loaded Event */
/* Dark Syntax */

using (var Client = new WebClient { Proxy = null })
using (var XmlTextReader = new XmlTextReader(Client.OpenRead("https://raw.githubusercontent.com/ImmuneLion318/Editor-Syntax/Entry/Syntax/Dark.xshd")))
       Editor.SyntaxHighlighting = HighlightingLoader.Load(XmlTextReader, HighlightingManager.Instance); 
```

```csharp
/* Call On Loaded Event */
/* Light Syntax */

using (var Client = new WebClient { Proxy = null })
using (var XmlTextReader = new XmlTextReader(Client.OpenRead("https://raw.githubusercontent.com/ImmuneLion318/Editor-Syntax/Entry/Syntax/Light.xshd")))
       Editor.SyntaxHighlighting = HighlightingLoader.Load(XmlTextReader, HighlightingManager.Instance); 
```
