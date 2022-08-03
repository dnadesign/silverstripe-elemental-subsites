# Silverstripe Elemental Subsites

[![CI](https://github.com/dnadesign/silverstripe-elemental-subsites/actions/workflows/ci.yml/badge.svg)](https://github.com/dnadesign/silverstripe-elemental-subsites/actions/workflows/ci.yml)
[![Silverstripe supported module](https://img.shields.io/badge/silverstripe-supported-0071C4.svg)](https://www.silverstripe.org/software/addons/silverstripe-commercially-supported-module-list/)

This module adds [subsite](https://github.com/silverstripe/silverstripe-subsites) support for 
[elemental](https://github.com/dnadesign/silverstripe-elemental).

```yaml
ElementPage:
  extensions:
    - DNADesign\ElementalSubsites\Extensions\ElementalSubsitePageExtension

DNADesign\Elemental\Models\BaseElement:
  extensions:
    - DNADesign\ElementalSubsites\Extensions\ElementalSubsiteExtension
```
