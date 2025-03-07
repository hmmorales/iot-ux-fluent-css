# CHANGELOG
## v8.2.1
### Changed
- Added an additional instance of _colors with the file extensions .scss as IoTC is now using sass as opposed to node-sass and .scss are required to render styles.

## v8.2.0
### Changed
- Updated colors to match fluent colors for light theme
- Added `--color-global-background-severe-warning` and `--color-global-foreground-severe-warning`
- Added `color-scheme` and `accent-color` CSS rules to themes to have a better default browser support.
- Added support for `IGNORE-SECTION` on codegen code to allow for CSS rules on theme files.

## v8.1.13
### Changed
- Added `--color-foreground-primary`

## v8.1.12
### Changed
- Updated `--color-search-background` to be 85% white
- Added `--color-search-text`
- Updated `--color-search-text-hover`
- Updated `--color-search-text-placeholder`
- Added `--color-search-text-placeholder-selected`

## v8.1.11
### Changed
- Added global class ellipsis-left to display tree structure-type items where the
text at the end of the string is more relevant than the text at the beginning

## v8.1.10
### Changed
- Added $size-75 sizing constant (6rem)

## v8.1.9
## Fixed
- Make HTML be the only one to take available space, all the other elements take 100%.
- Include nextjs root element in normalize CSS for react root.

## v8.1.8
### Changed
- Fixed app height on webkit based browsers to take all available space instead of 100vh

## v8.1.7
### Changed
- Updated `$max-size-60` to 46.25rem

## v8.1.6
### Changed
- Added `--color-content-background-tertiary` to be used as background below cards
- Added `$space-default`
- Updated `H1` typography size and line height
- Updated `$max-size-90` to 120rem

## v8.1.5
### Changed
- Added new `$size-115` and `$max-size-90` that accomodate for needs in page templates.

## v8.1.4
### Changed
- Remove unused semi-transparent colors.

## v8.1.3
### Changed
- Update `focus-visible` outline color from `foreground-default` to `foreground-inactive`

## v8.1.2
### Changed
- Update `focus-visible` class to align to FluentUI
- Remove focus states on anchor tags normalization

## v8.1.1
### Changed
- Updated color section from `IoTC internal data viz` to `IoTC visualizations`

## v8.1.0
### Changed
- Updated `_normalize.scss` to use new spacing and sizing constants.
- Removed unused dl and dt normalization.
- Removed unused `--font-family-din-regular`
- **[BREAKING]** Changed `--font-family-light` to `--font-family-semilight`
- Marked old spacing classes as deprecated in favor of new ones.
- Marked `%semibold` as deprecated in favor of `.semibold` css class and added a `.semilight` class
- **[BREAKING]** Changed `--line-weight-headings` to `--line-weight-semibold`
- **[BREAKING]** Changed `--line-weight-hero` to `--line-weight-semilight`
- **[BREAKING]** Moved media query breakpoints to its own `_responsive.scss` file, updated breakpoints to align to fluent and added mobile first mixins to easily use these breakpoints.
- Removed unused `box-sizing` and `tab-focus` mixins.
- Updated `--font-size-hero`, `--line-height-hero`, `--font-size-h1` and `--line-height-h1` to align to fluent.

### Added
- Added new spacing and sizing constants to align to new design system.
- Added `.focus-visible` class to unify keyboard only focus behavior where supported (fallback to regular focus behavior)
- Added IoTC internal data viz colors for system defined visualization coloring.

## v8.0.6
### Changed
- Updated `--color-search-background` to `--color-light-transparent-tenth` in both light and dark
- Updated `--color-status-success` and `--color-status-warning` in light mode to increase hue.

## v8.0.5
### Added
- Content background featured color for the background area behind featured items, to make them stand out and more distinct from the rest.

## v8.0.4
### Fixed
- Foreground disabled, selected hover and foreground inactive in dark to have better contrast

### Changed
- Added separate colors for links to not use accent color and modified normalize to use them

## v8.0.3
### Changed
- Removed deprecated colors

## v8.0.2
### Changed
- Added shimmer colors
- Added foreground tertiary for less important separations
- Removed utils generated file since it's not needed with dynamic stylesheet generation approach

## v8.0.1
### Changed
- Change non-scss files to use css
- Added codegen to generate theme-related typescript files

## v8.0.0
### Changed
- Deprecated mapping and made each theme to have its own palette that shares the same naming convention

## v7.1.3
### Changed
- Changed `--color-text-active` in `dark/_color.fluent.scss` to `--color-white`

## v7.1.2
### Fixed
- Added sufficient contrast to toggle on dark theme.

## v7.1.1
### Changed
- Updated `$layout-nav-item-height` to align with office fabric's fluent command bar update.

## v7.1.0
### Changed
- RTL is now handled by using the `dir` attribute in the root html element.

## v7.0.4
### Fixed
- `--color-bg-loading-panel` color in dark mode to be a darker grey to decrease its contrast

## v7.0.3
### Fixed
- Reverted container color change made in v7.0.2
- Added appropriate dashboard background color.

## v7.0.2
### Changed
- Container background color in light color to be light gray instead of white

## v7.0.1
### Fixed
- Rename fluent themes to default names
- Make light theme the default

## v7.0.0
### Changed
- Moved to CSS Custom Properties
- Moved sizes to rem
- Adopted fluent colors

## v6.0.0
### Added
- Media query breakpoints

### Changed
- Various colors to match the new design language.

## v5.0.2
### Changed
- reverted changes on color background input for dark-theme

## v5.0.1
### Changed
- changed to transparent the color background on input for dark-theme

## v5.0.0
### Changed
- remove font files
- remove icons.scss

## v4.0.0
### Changed
- move to @microsoft npm scope

## v3.0.4
### Added
- colors for title bars

## v3.0.3
### Fixed
- danger button should have a white outline

## v3.0.2
### Fixed
- add color for primary button focus
- change license from ics to mit

## v3.0.1
### Fixed
- new green for success on light theme

## v3.0.0
### Changed
- npm scope from @microsoft to @azure-iot

## v1.1.0
### Added
- hover colors for alert close button

## v1.0.0
- initial