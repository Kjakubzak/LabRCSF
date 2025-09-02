# Reference Canonical Skeletal Framework

Copyright 2025 Nick Porcino

## Purpose

The Reference Canonical Skeletal Framework (RCSF) addresses the critical interoperability challenge facing humanoid character systems across digital content creation, game development, and metaverse applications. Through comprehensive analysis of major skeletal standards—from production animation systems to research frameworks—this project provides systematic approaches for cross-format compatibility while preserving the specialized optimizations that drive format diversity.

This framework provides synthesis-based solutions through comprehensive intermediate representations that enable principled conversion between diverse humanoid skeletal formats. Rather than enforcing universal standardization, RCSF maintains the technical advantages of format-specific optimizations while establishing translation infrastructure for seamless content exchange across application domains.

## Contents

- `survey.md` - Comprehensive analysis of humanoid skeletal standards across nine major formats including OpenUSD, VRM, HAnim, SMPL-X, BVH, ASF/AMC, Mixamo, UE Mannequin, and Unity Mecanim
- `joints.csv` - Complete cross-format mapping table showing semantic correspondence between 127 canonical joints across all analyzed standards
- `proposal.md` - Metaverse Standards Forum proposal for RCSF adoption, including strategic implementation pathways and stakeholder benefits
- `references.md` - Primary information sources for each of the studied formats
- `README.md` - This overview document

## Tasks

Validate each of the format descriptions:

- [ ] OpenUSD - Pixar Universal Scene Description skeletal framework
- [ ] VRM - VRoid humanoid avatar specification  
- [ ] HAnim - Web3D Consortium humanoid animation standard
- [ ] SMPL-X - Statistical Multi-Person Linear model eXpressive
- [ ] BVH - Biovision Hierarchy motion capture format
- [ ] ASF/AMC - Acclaim motion capture format
- [ ] Mixamo - Adobe automated animation service
- [ ] UE Mannequin - Unreal Engine reference skeleton
- [ ] Unity Mecanim - Unity semantic humanoid system

Create Tools

- [ ] CSV-to-mapping-algorithm converter
- [ ] Joint hierarchy validation tool
- [ ] Cross-format conversion engine
- [ ] Anatomical consistency validator
- [ ] Animation quality assessment framework
- [ ] Performance benchmarking suite
- [ ] Community validation platform
- [ ] Reference implementation library

Research Documentation

- [x] Locate primary SMPL-X academic publications and implementation repositories
- [x] Find original BVH format specifications and comprehensive documentation
- [x] Locate CMU ASF/AMC format documentation and motion capture database references
- [x] Find Adobe Mixamo technical documentation and API specifications
- [x] Locate Epic Games UE Mannequin skeletal system documentation
- [x] Find Unity Mecanim Humanoid Animation system technical documentation
- [x] Verify and update all reference links for accuracy and completeness

RFC

- [ ] How should twist bones be handled in minimal target formats?
- [ ] What constitutes acceptable quality loss during downward conversion?
- [ ] Should facial expression joints use standardized blendshape names?
- [ ] How do we handle proprietary engine-specific features (Animation Blueprints, etc.)?
- [ ] What validation metrics best assess cross-format conversion quality?
- [ ] How should the framework accommodate emerging standards (VR haptics, AI-driven animation)?
- [ ] What governance model ensures long-term framework evolution?
- [ ] Should there be performance tiers for different hardware capabilities?

## License

Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. You are free to share and adapt this material for any purpose, even commercially, under the following terms:
- **Attribution** - You must give appropriate credit and indicate if changes were made
- **ShareAlike** - If you remix, transform, or build upon the material, you must distribute your contributions under the same license

This license promotes collaborative development while ensuring that improvements benefit the broader community working on humanoid skeletal interoperability challenges.
