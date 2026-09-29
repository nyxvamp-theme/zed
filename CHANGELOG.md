# Changelog

All notable changes to the NyxVamp Zed theme will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0] - 2026-09-28

### Added

- New variant: NyxVamp Jhujuba, a pink-tinted mid-dark theme between veil and radiance

### Changed

- **Veil**: comment gray `#6E6A86` to `#8C88A6`; constants and booleans from pink `#F28FAD` to gold `#E1C487`
- **Obsidian**: comment gray `#5E5A76` to `#8682A0`; constants and booleans from pink `#F28FAD` to gold `#D7BA7D`
- **Radiance**: contrast fixes from the palette audit: string `#B8860B` to `#825B00`, keyword purple `#9655FF` to `#7743CC`, type purple `#6B46C1` to `#4657BD`, hint cyan `#8BD5CA` to `#2B7068`, conflict red `#E78284` to `#A43A41`
- **All variants**: namespace now uses the type color instead of the keyword color, matching the canonical Helix theme

## [0.2.1] - 2025-08-26

### Fixed

- UI contrast specially on selected items on cmd palette/file tree fixes

## [0.2.0] - 2025-08-26

### Major Theme Overhaul

#### Added

- Strict Base16 color palette compliance across all variants
- Improved GUI-specific visual elements for Zed editor
- Enhanced contrast ratios for better accessibility
- Semantic color mapping following Base16 standards

#### Changed

- **All Variants**: Complete UI color scheme overhaul for better readability
- **Radiance**: Applied improved contrast colors from Helix refactor
- **Veil**: Fixed element backgrounds (`#302D41` � `#2E2E3E`) to match Helix implementation
- **Obsidian**: Aligned all UI elements with Base16 color slots
- **Syntax Highlighting**: Enhanced semantic color differentiation using proper Base16 mapping
  - `base08` (red) � constants, booleans, errors
  - `base09` (orange) � numbers, warnings
  - `base0A` (yellow) � strings, success states
  - `base0B` (green) � functions, info states
  - `base0D` (blue) � keywords, attributes
  - `base0E` (purple) � operators, types

#### Fixed

- Border visibility issues in GUI environment
- Tab differentiation (active vs inactive) across all variants
- Scrollbar contrast ratios for better mouse interaction
- Status bar background contrast
- Focus indicators for keyboard navigation
- Namespace colors to match Base16 standards
- Diagnostic colors alignment with Base16 palette
- Visual hierarchy between similar UI elements

#### Improved

- GUI contrast for better mouse navigation
- Color accessibility meeting WCAG standards
- Consistency between Helix and Zed implementations
- Visual separation of UI components

### Technical Changes

- Updated all color values to strictly follow Base16 specification
- Enhanced theme structure for better maintainability
- Improved semantic color assignments

---

## [0.1.0] - 2024-11-01

### Added

- Initial port of NyxVamp theme to Zed editor
- Three variants: Radiance (light), Veil (dark), Obsidian (darker)
- Basic syntax highlighting support
- Core UI element theming

### Features

- Support for all major programming languages
- Consistent color scheme across variants
- Basic GUI element styling
