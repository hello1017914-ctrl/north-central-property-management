---
version: alpha
name: Elite Property Maintenance
author: Elite Property Maintenance LLC
description: A professional, modern website for veteran-owned property maintenance business with bold, rugged American service-business aesthetic.
colors:
  primary: "#2d5016"  # Deep forest green
  primary-60: "#7bb541"  # Vivid grass green
  secondary: "#000000"  # Black
  tertiary: "#ffffff"  # White
  neutral: "#ffffff"  # White surface
  surface: "#ffffff"  # White surface
  on-surface: "#0a1f0a"  # Dark green for text
  border: "#e8f5e8"  # Light green border
  error: "#dc2626"  # Red for errors
  veteran-red: "#dc2626"  # Red for veteran branding
  veteran-white: "#ffffff"  # White for veteran branding
  veteran-blue: "#1e40af"  # Blue for veteran branding
typography:
  headline-display:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "56px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-1px"
  headline-lg:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "42px"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.5px"
  headline-md:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "32px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "-0.25px"
  headline-sm:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0px"
  body-lg:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0px"
  body-md:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0px"
  body-sm:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "0px"
  label-lg:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0px"
  label-md:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "14px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0px"
  label-sm:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "0px"
  link-sm:
    fontFamily: "Inter, system-ui, -apple-system, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: "0px"
rounded:
  none: 0px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px
spacing:
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 32px
  section: 80px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.md}"
    padding: "16px 32px"
    height: "56px"
    hover:
      backgroundColor: "{colors.primary-60}"
  button-secondary:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label-lg}"
    rounded: "{rounded.md}"
    padding: "16px 32px"
    height: "56px"
    border:
      width: "2px"
      color: "{colors.primary}"
    hover:
      backgroundColor: "{colors.tertiary}"
  button-tertiary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.none}"
    padding: "0px"
    hover:
      textDecoration: "underline"
  button-veteran:
    backgroundColor: "{colors.veteran-red}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.sm}"
    padding: "4px 12px"
    height: "32px"
    hover:
      backgroundColor: "{colors.veteran-red}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: "24px"
    border:
      width: "1px"
      color: "{colors.border}"
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: "12px 16px"
    border:
      width: "1px"
      color: "{colors.border}"
    focus:
      borderColor: "{colors.primary}"
      outline: "none"
  chip:
    backgroundColor: "{colors.veteran-blue}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.full}"
    padding: "6px 16px"
    margin: "4px"
  link:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.label-md}"
    rounded: "{rounded.none}"
    padding: "0px"
    hover:
      textDecoration: "underline"
  badge:
    backgroundColor: "{colors.veteran-red}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-sm}"
    rounded: "{rounded.sm}"
    padding: "4px 8px"
    margin: "4px"
  service-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.lg}"
    padding: "32px"
    border:
      width: "1px"
      color: "{colors.border}"
    hover:
      transform: "translateY(-4px)"
      boxShadow: "0 20px 25px -5px rgba(0, 0, 0, 0.1)"
# Elite Property Maintenance Brand Guidelines

## Overview
A bold, rugged, trustworthy American service-business aesthetic for a veteran-owned property maintenance company. The design balances professional polish with approachable service culture, emphasizing reliability and quality workmanship.

## Color System
- **Primary (#2d5016):** Deep forest green representing reliability, growth, and trust
- **Primary-60 (#7bb541):** Vivid grass green for secondary accents and freshness
- **Secondary (#000000):** Black for bold, professional elements
- **Tertiary (#ffffff):** White for clean, spacious layouts
- **Veteran Colors:** Red (#dc2626), White (#ffffff), Blue (#1e40af) used sparingly for veteran-owned messaging

## Typography
The system uses Inter font for modern, clean readability with plenty of whitespace. Bold headings establish hierarchy while maintaining approachability.

## Layout
Wide, centered content with substantial breathing room. Service cards and components use measured padding to create a premium feel. Vertical rhythm guides the layout with generous spacing between sections.

## Elevation & Depth
Minimal elevation - depth comes from color contrast, whitespace, and subtle hover effects rather than heavy shadows. Buttons and cards use color fill and hover states for interaction feedback.

## Shapes
Consistent 6px-12px radii for buttons, cards, and inputs. Full rounding reserved for veteran badge and service chips. Clean, architectural rather than playful.

## Components
Buttons use the forest green primary color as the main call-to-action. Secondary buttons use white with green borders. Veteran-specific elements use red, white, and blue minimal accents.

## Do's and Don'ts
- Do maintain generous whitespace for premium feel
- Do use forest green as primary trust color
- Do feature veteran-owned elements prominently
- Don't use too much red, white, blue (just for veteran branding)
- Don't clutter hero sections
- Don't use overly playful shapes or animations

## Services
Each service should be presented with clear imagery, concise descriptions, and specific benefits. Service cards should hover and provide clear CTAs.

## Contact
Phone-first approach with clear, large contact information. Form should be simple and focused on capturing leads.

## Footer
Simple footer with quick navigation links and contact information. No unnecessary decorative elements.