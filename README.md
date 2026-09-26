# Intel Sustainability: Localized

A localized version of my Intel sustainability timeline. It adds an English/Arabic language switcher with a full right-to-left (RTL) layout, along with new sections built with Bootstrap.

**🔗 Live site:** https://dishaabhat08.github.io/03-project-intel-localization/

## About

This project builds on my [Intel Sustainability Through the Ages](https://github.com/dishaabhat08/02-prj-intel-sustainability) timeline. The goal was to make the site work for a global audience. Visitors can switch between English and Arabic, and the whole page, including the text, layout direction and icons, flips to fit the reading direction of the selected language.

## Features

- **Language switcher:** swap between English and العربية
- **Right-to-left support:** uses Bootstrap's RTL stylesheet and `dir="rtl"`, so the layout, alignment and arrows mirror correctly
- **Sustainability goals section:** cards covering Intel's RISE strategy, net-zero commitment, and water and waste work
- **FAQ accordion:** quick answers to common questions, built with Bootstrap's accordion component
- **Newsletter signup form:** styled with Bootstrap form components
- **Interactive timeline:** hover or focus cards to see more detail, with scroll snap
- **Responsive and accessible:** mobile-friendly layout, a skip link, keyboard focus styles and reduced-motion support

## Built With

- HTML5
- CSS3
- JavaScript
- [Bootstrap 5.3](https://getbootstrap.com/) (including the RTL build)
- Bootstrap Icons

## What I Learned

- How localization differs from translation: layout direction, alignment and icon direction all have to change
- Using `dir` and `lang` attributes and `[dir="rtl"]` CSS selectors to support right-to-left languages
- Using a CSS framework like Bootstrap to build components faster while keeping a custom design
