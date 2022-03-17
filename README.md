# marketingpage-code-refactor
code refactor for marketing agency

Added accessibility standards as follows:
- alt tags added to all images and icons

Added the following semantic HTML Elements
- Changed <div>'s with class of ".header" to HTML semantic<header>
- Changed <div>'s that served as a navigation bar to HTML semantic <nav>
- Changed <div>'s with class of ".benefits" to HTML semantic <aside>
- Changed <div> with class of ".content" to HTML semantic <main>
- Changed <div>'s breaking up content sections within <main> to <section>'s
- Changed <div> with class of ".footer" to HTML semantic <footer>

Condensed the following CSS Selectors
- Condensed multiple selectors with classes named .benefits-xxx to single h3 selector
- 

To-Do:
- Continue to codense multiple css classes to single classes (lines 69-94, 119-131, and 156-172)
- Condense multiple classes with img tags (176) [aside img or unique]
- Condense multiple classes with h2 tags (188)  [aside h2 or unique class]