# marketingpage-code-refactor
code refactor for marketing agency

### Added accessibility standards as follows:
- alt tags added to all images and icons within HTML document
- Condense title optimized for SEO

### Added the following semantic HTML Elements
- Changed div tags with class of ".header" to HTML semantic header tag
- Changed div tags that served as a navigation bar to HTML semantic nav tag
- Changed div tag with class of ".benefits" to HTML semantic aside tag
- Changed div tag with class of ".content" to HTML semantic main tag
- Changed div tags breaking up content sections within main to section tags
- Changed div tags with class of ".footer" to HTML semantic footer tag

### Condensed the following CSS Selectors
- Condensed multiple selectors with classes named .benefits-xxx to singular, universal class ".benefit-aside-style"
- Condensed multiple selectors within section tags to a singlular, universal class ".main-section-content"
- Deleted unused id's in main content section
- Reorganized style.css selectors to follow a logical flow
