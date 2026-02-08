## 2.0.0
- package no longer holds the source code for it, but exports/exposes the `s_packages` package instead, which will hold this package's latest source code.
- The only future changes to this package will be made via `s_packages` package dependency upgrades, in order to bring the new fixes or changes to this package
- dependent on `s_packages`: ^1.1.2


## 1.0.0

Initial release of s_context_menu package.

### Features

- Advanced context menu widget with right-click (Web or desktop) and long-press (mobile) support
- Animated fade and scale transitions for smooth UX
- Automatic smart positioning with intelligent arrow placement
- Accessibility features including screen reader support and semantic labels
- Overflow handling with scrollable menu content when needed
- Keyboard navigation and ESC key support for closing
- Comprehensive theming system for customization
- Multi-open mode for displaying multiple menus simultaneously
- Lifecycle callbacks (onOpened, onClosed) for menu state tracking
- Programmatic menu control via static helper methods
- Modern glassmorphic design with backdrop blur effect
- Full keyboard support with arrows, ENTER/ESC keys navigation


