AVIELLE CHAT — GitHub Pages package

FILES
- index.html: standalone page (open/edit directly in GitHub)
- assets/avielle-logo.webp: optimized brand logo
- assets/favicon.png: browser/tab and Apple touch icon
- assets/avielle-og.jpg: Open Graph preview image

PUBLISH
1. Upload index.html and the assets/ folder to the ROOT of your GitHub Pages repository.
2. In index.html, search for YOUR-GITHUB-USERNAME and YOUR-REPOSITORY. Replace both placeholders in og:image, og:url and twitter:image with your real GitHub Pages URL. Social crawlers require absolute, publicly reachable image URLs.
3. SMS uses sms:+255749094858 with the prefilled message: “Habari, nataka unijuze kuhusu Avielle Chat”. Device/browser support for prefilled SMS can vary.

PERFORMANCE
- Replaced embedded multi-megabyte logo with optimized WebP asset.
- Removed external Google Fonts dependency; system font stack is used.
- Profile photos remain remote RandomUser images and load lazily/async to avoid fetching all photos immediately.

NOTE
All existing profile content, layout, account gate, registration link and chat demo flow are retained. This is a front-end demo; the verification screen is not connected to a real account backend.
