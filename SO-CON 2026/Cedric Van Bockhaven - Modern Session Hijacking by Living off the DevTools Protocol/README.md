# Modern Session Hijacking by Living off the DevTools Protocol

**Speaker:** Cedric Van Bockhaven

## Abstract

Modern browser defenses are raising the bar for traditional cookie and session theft, introducing protections such as App-Bound Encryption and stricter runtime policies, but they don’t stop on-device attackers. This talk explores how the DevTools Protocol (CDP) can be used offensively to get around those defenses. Normally, this requires restarting a Chromium-based browser with custom command-line flags and hoping Group Policy hasn’t disabled remote debugging entirely.

This session presents new research that skips those built-in checks by injecting custom shellcode into a live browser, locating specific internal C++ routines via pattern matching, and enabling DevTools in-process. With CDP access in hand, we explore how the DevTools API can be abused in practice. Pulling cookies directly from the running browser is the starting point. On top of that, this research introduces new techniques for remote browsing in a CursedChrome-style fashion (for example logging into Microsoft 365 as the victim), and a new attacker-in-the-middle capability that intercepts and modifies requests and responses, all tunneled over CDP.

## Track

Tradecraft

## Tags

- Offensive
- Identity
- Browser
