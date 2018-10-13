# Updated Irrlicht Lime for [Wolven kit](https://github.com/Traderain/Wolven-kit)

Irrlicht Lime is a .NET wrapper for the Irrlicht Engine.

This version of Irrlicht Lime is a modified version of the original Irrlicht Lime (v1.5) which was created by the respective owners:
- https://sourceforge.net/projects/irrlichtlime/


### Changes
The following changes were made in the source code in order to support SkinnedMesh Joints which is used by [Wolven kit's Renderer](https://github.com/Traderain/Wolven-kit/tree/master/WolvenKit.Render):
- Added [SJoint.cpp](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SJoint.cpp)
- Added [SJoint.h](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SJoint.h)
- Added [SPositionKey.cpp](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SPositionKey.cpp)
- Added [SPositionKey.h](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SPositionKey.h)
- Added [SRotationKey.cpp](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SRotationKey.cpp)
- Added [SRotationKey.h](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SRotationKey.h)
- Added [SScaleKey.cpp](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SScaleKey.cpp)
- Added [SScaleKey.h](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SScaleKey.h)
- Added [SWeight.cpp](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SWeight.cpp)
- Added [SWeight.h](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SWeight.h)
- Modified [SkinnedMesh.cpp](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SkinnedMesh.cpp)
- Modified [SkinnedMesh.h](https://github.com/kote2ster/Irrlicht-Lime-for-Wolven-kit/blob/master/source/SkinnedMesh.h)

Original readme is in [readme.txt](/readme.txt)
