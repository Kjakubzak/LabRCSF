# Primary Information Sources

This document lists the primary documentation sources for each skeletal format analyzed in the Reference Canonical Skeletal Framework study.

## OpenUSD (Universal Scene Description)

**Official Documentation:**

- UsdSkel API Documentation - https://openusd.org/dev/api/usd_skel_page_front.html
- UsdSkel Introduction - https://openusd.org/dev/api/_usd_skel__intro.html
- UsdSkel API Introduction - https://openusd.org/dev/api/_usd_skel__a_p_i__intro.html
- UsdSkel Schemas In-Depth - https://openusd.org/dev/api/_usd_skel__schemas.html
- UsdSkel Schema Overview - https://openusd.org/dev/api/_usd_skel__schema_overview.html
- UsdSkel Examples - https://openusd.org/release/dl_usdskel_examples.html

**Description:** UsdSkel defines schemas and API that form a basis for interchanging both skeletally skinned meshes and joint animations between DCC tools in a graphics pipeline. UsdSkel provides an encoding of simple skeletons and blend shapes, with the goal of interchanging basic skeletons and skinned models, both for game studios as well for the performant, scalable interchange of large-scale crowds.

## VRM (Virtual Reality Model)

**Official Documentation:**

- VRM Official Website - https://vrm.dev/en/
- VRM Consortium - https://vrm-consortium.org/en/
- GitHub Specification Repository - https://github.com/vrm-c/vrm-specification _(referenced in search results but requires direct access)_
- Library of Congress Format Description - https://www.loc.gov/preservation/digital/formats/fdd/fdd000564.shtml

**Third-Party Documentation:**

- Converting an avatar to VRM format (Community Guide) - https://gist.github.com/emilianavt/51d8399987d67544fdebfe2ebd9a5149
- Animaze VRM Integration Documentation - https://www.animaze.us/manual/vrmavatar/vrmanimations

**Description:** VRM is a platform-independent file format designed for use with 3D characters and avatars in the modern VR landscape. VRM is based on glTF2.0 and can be freely used by anyone. In addition, there is an open source standard implementation in C# (UniVRM) for reading and writing VRM files for Unity.

## HAnim (Humanoid Animation)

**Official Documentation:**

- HAnim Working Group (Web3D Consortium) - https://www.web3d.org/working-groups/hanim
- All HAnim Standards - https://www.web3d.org/new/standards/hanim
- HAnim Architecture V2 - https://www.web3d.org/content/hanim-architecture-v2
- HAnim Motion Data V2 - https://www.web3d.org/content/hanim-motion-data-v2
- HAnim GitHub Repository - https://github.com/x3d/HumanoidAnimation

**Standards Reference:**

- ISO/IEC 19774 - Humanoid Animation (H-Anim) _(ISO standard, requires purchase)_
- ISO/IEC 19775-1 X3D Component 26 Humanoid Animation (HAnim)

**Description:** HAnim supports a wide variety of articulated figures, including anatomically correct human models, incorporating haptic and kinematic interfaces in order to enable sharable skeletons, bodies and animations.

## SMPL-X (Statistical Multi-Person Linear Model eXpressive)

**Official Documentation:**

- SMPL-X Website (MPI-IS) - https://smpl-x.is.tue.mpg.de (model downloads, licenses, and integration materials)
- GitHub Repository: vchoutas/smplx - https://github.com/vchoutas/smplx (official implementation, parameters, installation)
- SMPL-X Model License - https://smpl-x.is.tue.mpg.de/license (non-commercial/academic terms)

**Academic Publications:**

- Pavlakos et al. "Expressive Body Capture: 3D Hands, Face, and Body from a Single Image" (CVPR 2019) - https://arxiv.org/abs/1904.05866

**Description:** SMPL-X extends the SMPL body model with fully articulated hands and an expressive face, enabling unified modeling of body pose, hand gestures, and facial expressions. The model supports 127 joints total (24 body + 30 hand + 51 face + 22 additional articulation).

## BVH (Biovision Hierarchy)

**Primary Documentation:**

- Wikipedia — Biovision Hierarchy - https://en.wikipedia.org/wiki/Biovision_Hierarchy (general overview, structure, and adoption)
- FileFormat.com — BVH File Format - https://www.fileformat.com/3d/bvh (technical description and software integration)
- CityU Technical Reference - http://www.cs.cityu.edu.hk/~howard/Teaching/CS4185-5185-2007B/Group12/BVH.html (hierarchical structure documentation)

**Description:** BVH (Biovision Hierarchy) is a file format for storing motion capture data that contains both skeletal hierarchy information and animation data. The format consists of two main sections: HIERARCHY (defines skeleton structure and joint relationships) and MOTION (contains time-series transformation data).

## ASF/AMC (Acclaim Skeleton + Motion Capture Format)

**Primary Documentation:**

- University Format Overview - http://research.cs.wisc.edu/graphics/Courses/cs-838-1999/Jeff/ASF-AMC.html (Acclaim format skeleton + motion structure)
- Carnegie Mellon Documentation - http://graphics.cs.cmu.edu (CMU Graphics Lab motion capture database)
- Wikipedia - List of Motion and Gesture File Formats (ASF/AMC file pair description)
- Python CGKit asfamc Module - http://cgkit.sourceforge.net (ASF/AMC parsing implementation via ASFReader classes)
- Darwin 3D Academic Specification - ResearchGate (mocap file formats overview, Euler conventions)

**Tool-Specific Documentation:**

- Autodesk MotionBuilder Limitations - Autodesk Help (import/export quirks, SphericXYZ rotation order limitations)

**Description:** ASF/AMC separates skeleton definition (.ASF) from motion data (.AMC). ASF files contain joint hierarchy, degrees of freedom, and bone lengths, while AMC files contain time-series animation data for the defined skeleton.

## Mixamo

**Primary Documentation:**

- Mixamo Website (Adobe) - https://www.mixamo.com (Auto-Rigger, animation store, service documentation)
- Epic Games Unreal Engine Integration - https://docs.unrealengine.com (Mixamo Content usage, animation retargeting guides)

**Integration Documentation:**

- Omniverse Integration Tutorials - NVIDIA Developer documentation
- Blender Integration Guides - Community tutorials for Mixamo-to-Blender workflows
- Ready Player Me Integration - https://docs.readyplayer.me (avatar system integration with Mixamo)

**Description:** Mixamo provides cloud-based auto-rigging and animation services with a standardized skeletal structure optimized for automated motion retargeting across diverse character models.

## UE Mannequin (Unreal Engine)

**Primary Documentation:**

- Unreal Engine Documentation - https://docs.unrealengine.com/skeletons (Skeletal hierarchy, skeleton assets, skeletal mesh assets)
- Epic Games Developer Community - https://dev.epicgames.com (Skeletal Editor tutorials, IK setup, bone structure guides)

**Community Documentation:**

- Epic Games Forums - Developer community discussions on mannequin bone structure and usage
- Reddit Community Insights - Community explanations of mannequin purpose and animation retargeting

**Description:** The UE Mannequin provides a standardized humanoid skeleton structure within Unreal Engine, designed for consistent animation retargeting and performance optimization across game development workflows.

## Unity Mecanim

**Primary Documentation:**

- Unity Manual - https://docs.unity3d.com/Manual/MecanimAnimationSystem.html (Mecanim Animation System, humanoid rig setup, retargeting)
- Unity Developer Blog - Unity blog posts on Mecanim humanoid technology and implementation details

**Integration Documentation:**

- AAAnimators Tutorials - https://aaanimators.com (Unity avatar mapping, humanoid setup guides)
- Unity Learn Platform - Official Unity tutorials on avatar definitions and humanoid mapping

**Description:** Unity Mecanim provides semantic role-based humanoid animation through Avatar abstraction, enabling automatic retargeting between diverse skeletal rigs through standardized anatomical role mapping.

## Godot SkeletonProfileHumanoid

**Primary Documentation:**

- Godot Engine Documentation - https://docs.godotengine.org/en/stable/classes/class_skeletonprofilehumanoid.html

**Description:** Godot's SkeletonProfileHumanoid class defines a preset SkeletonProfile that is optimized for the human form. It contains 56 bones divided into 4 groups.

## Second Life

**Primary Documentation:**

Locked wiki pages (read-only for non-admins):

- https://wiki.secondlife.com/wiki/Project_Bento_Skeleton_Guide
- https://wiki.secondlife.com/wiki/Mesh/Troubleshooting
- https://wiki.secondlife.com/wiki/Appearance_Editor_and_affected_bones

**Community Documentation:**

- https://avalab.org/avastar/279/knowledge/the-sl-skeleton/
- https://community.secondlife.com/forums/topic/40196-joint-names/

---

## Roblox

**Primary Documentation:**

- R15 Character Specifications - https://create.roblox.com/docs/art/characters/specifications
- Rigging Guide - https://create.roblox.com/docs/art/modeling/rigging
- Facial Animation Overview - https://create.roblox.com/docs/art/characters/facial-animation
- Creating Basic Heads - https://create.roblox.com/docs/art/characters/facial-animation/create-basic-heads
- Adding Face Bones (DynamicHead) - https://create.roblox.com/docs/art/characters/facial-animation/create-basic-heads#add-face-bones
- Animating Heads - https://create.roblox.com/docs/art/characters/facial-animation/animate-heads

**Description:** Roblox R15 skeleton provides a simplified 15-joint body hierarchy optimized for user-generated content. The optional DynamicHead joint serves as the root for facial animation, allowing users to define custom child joints for FACS-based expressions.

---

## Momentum Human Rig

**Primary Documentation:**

- GitHub Repository: facebookresearch/MHR - https://github.com/facebookresearch/MHR
- GitHub Repository: facebookresearch/sam-3d-body - https://github.com/facebookresearch/sam-3d-body
- Meta AI Research Publication: SAM 3D Body - https://ai.meta.com/research/publications/sam-3d-body-robust-full-body-human-mesh-recovery/

**Description:** The Momentum Human Rig (MHR) is a high-fidelity humanoid skeleton designed for professional motion capture and animation production. It features 127 joints with extensive twist bone chains (5 per upper limb segment, 4 per lower limb segment) for smooth deformation, detailed foot anatomy (talocrural, subtalar, transverse tarsal joints), full finger articulation with metacarpals, and a 5-segment tongue for speech animation.

---

## Research Notes

Several formats lack easily accessible primary documentation sources:

1. **Academic/Research Formats** (SMPL-X, ASF/AMC) may require access to academic databases and conference proceedings
2. **Commercial Formats** (Mixamo, UE Mannequin, Unity Mecanim) require searching vendor documentation systems
3. **Historical Formats** (BVH, ASF/AMC) may have primary documentation that is archived or difficult to access

**Next Steps:** Systematic search for primary documentation sources for incomplete entries, with focus on official vendor documentation, academic publications, and authoritative technical specifications.
